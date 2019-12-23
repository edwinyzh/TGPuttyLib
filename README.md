# TGPuttyLib
A dynamic link library with Delphi and C++ bindings based on PuTTY

The new TGPuttyLib SFTP Library is a DLL conversion of the psftp program from the well-known PuTTY suite by Simon Tatham.

It allows developers to transfer files with the highest possible transfer rates (over 100MB/sec). The rates are higher than with any other known library.

TGPuttyLib is based on PuTTY Release 0.73. Ready-to-use classes are currently available for C++, Delphi and Free Pascal.

The library is currently available for Windows. MacOS and Linux adaptations will follow around the end of 2019.

For more information, please visit the project web site: 
https://www.syncovery.com/tgputtylib

---------------------
DIRECTORIES AND FILES
---------------------

tgputtylib.pas         -   Delphi Unit interfacing with the DLL

tgputtysftp.pas        -   Delphi SFTP Client Class (using 8-bit strings)

tgputtysftpclient.pas  -   Delphi SFTP Client Component (using UnicodeStrings)

ctgputtylib.cpp,h      -   C++ DLL bindings

tgputtylibcbclass.cpp,h    -  C++ Builder SFTP Client Class (using 8-bit strings)

tgputtycbsftpclient.cpp,h   -  C++ Builder Component (using UnicodeStrings)

tgputtylibvcclass.cpp,h   -  Visual C++ SFTP Client Class (using 8-bit strings)

---------------------

TGPuttyLib.dpk etc.    -   Delphi Package for SFTP Client Component

TGPuttyLibCPP.cbproj etc.  -  C++ Builder Package for SFTP Client Component

---------------------

DelphiSimpleDemos      -   Delphi Command Line Demos

DelphiVCLComponentDemo -   Fully working SFTP client application using the SFTP Client Component

DelphiVCLDemo          -   Fully working SFTP client application using the SFTP Client Class

FPCSimpleDemos         -   FPC Command Line Demos

CPPDemos               -   C++ Demos

---------------------

tgputtylib             -   DLL source code based on PuTTY

---------------------

bpl                    -   compiled Delphi Package for XE 10.3

Win32, Win64           -   compiled binaries
