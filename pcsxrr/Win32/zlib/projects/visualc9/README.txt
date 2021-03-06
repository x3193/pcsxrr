Microsoft Developer Studio Project File, Format Version 9.00 for zlib.

Copyright (C) 2004 Simon-Pierre Cadieux.
Copyright (C) 2004 Cosmin Truta.
For conditions of distribution and use, see copyright notice in zlib.h.


To use:

1) On the main menu, select "File | Open Solution".
   Open "zlib.sln".

2) Display the Solution Explorer view (Ctrl+Alt+L)

3) Set one of the project as the StartUp project. If you just want to build the
   binaries set "zlib" as the startup project (Select "zlib" tree view item +
   Project | Set as StartUp project). If you want to build and test the
   binaries set it to "example" (Select "example" tree view item + Project |
   Set as StartUp project), If you want to build the minigzip utility set it to
   "minigzip" (Select "minigzip" tree view item + Project | Set as StartUp
   project

4) Select "Build | Configuration Manager...".
   Choose the configuration you wish to build.

5) Select "Build | Clean Solution".

6) Select "Build | Build Solution (Ctrl-Shift-B)"

This project builds the zlib binaries as follows:

* Win32_DLL_Release\zlib1.dll       DLL build
* Win32_DLL_Debug\zlib1d.dll        DLL build (debug version)
* Win32_DLL_ASM_Release\zlib1.dll   DLL build using ASM code
* Win32_DLL_ASM_Debug\zlib1d.dll    DLL build using ASM code (debug version)
* Win32_LIB_Release\zlib.lib        static build
* Win32_LIB_Debug\zlibd.lib         static build (debug version)
* Win32_LIB_ASM_Release\zlib.lib    static build using ASM code
* Win32_LIB_ASM_Debug\zlibd.lib     static build using ASM code (debug version)

