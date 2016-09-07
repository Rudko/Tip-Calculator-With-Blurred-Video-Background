# Tip-Calculator-With-Blurred-Video-Background

Trying to use blurred preview from iPhone back camera as a background for an app (tip calculator, just testing the idea). When in separate projects – both blured preview and calculator work. When I combine them in one project – I see only white screen.  

As I understand Tap Gesture Recognizer (which I use in tip calculator app) can only be put in the first view. I actually need it in another view (3d one?) – the view containing calculator. Btw this view is also a part of Visual Effect View – may be I had to add calculator in a separate view and put it on a top of a previous one (Visual Effect View). 
Anyway Tap Gesture Recognizer is not critical for me. Even when I delete it and comment out it's function – I still see only a white screen when run the app on my iPhone.

The actual reason why Xcode terminates app – something wrong with totallabel. I can't understand what. Here is what Xcode says: 

Terminating app due to uncaught exception 'NSUnknownKeyException', reason: '[<testingSnapchatCamera.ViewController 0x14fe34fb0> setValue:forUndefinedKey:]: this class is not key value coding-compliant for the key totallabel.'
*** First throw call stack:
(0x1825fedb0 0x181c63f80 0x1825fea70 0x182f0b6e4 0x187ad5de8 0x187c38eb0 0x182522888 0x187c37898 0x187ad9230 0x18789e118 0x1877608ec 0x187760844 0x18776759c 0x187764a88 0x1877dafa4 0x187a063ac 0x187a0a5f0 0x187a07764 0x183f9f7ac 0x183f9f618 0x183f9f9c8 0x1825b509c 0x1825b4b30 0x1825b2830 0x1824dcc50 0x1877cf94c 0x1877ca088 0x10002588c 0x18207a8b8)
libc++abi.dylib: terminating with uncaught exception of type NSException
(lldb) 





