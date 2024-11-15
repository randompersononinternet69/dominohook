# dominohook
a hook dll for domino. what more is there to say?

this uses the excellent QuickHook library by CPunch, which can be found [here](https://github.com/CPunch/QuickHook)

note: only works for domino 1.43 at the moment, it will be rewritten to work for domino 1.44 and above once 1.45 becomes stable and (for now, anything above 1.43 will fail to launch)


## features
- replaced zoom handling functions
- string patching framework with translated strings by [@ryryjy](https://github.com/ryryjy)
- that's it for now...

## usage
1. compile the dll (x86/Release) or get a build from the releases page
2. use [Stud_PE](http://www.cgsoftlabs.ro/studpe.html) to add the dummy import to the domino exe
    * open it
    * drag the domino exe onto it
    * click the functions tab
    * right click the dll list
    * add new import
    * select the dll
    * add dummyexport to the list
3. copy the dll over to where domino is installed
4. hope that it doesn't crash
