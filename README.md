# FBX SDK for WinRT

This project goal is to provide a winMD projection to the Autodesk FBX SDK in order to use it from any C# or WinJS app.

# Why WinRT ?
WinRT provides a very lightweight and fast way to interop between languages. Compared to other technologies like C++ CLI, it provides a better C++ language support, and real object oriented metadata (making it far more useable from an object oriented language).
WinRT third party components can only been used from Universal Apps (for now). So for now, apps, tools, and games built from this SDK must be Store Apps.
But it is worth the effort : it's a good way to make these compatible for the broadest range of devices on Microsoft OS (from the phone, to the PC, and soon to the XBox One), and provides first class support for touch based interfaces.

