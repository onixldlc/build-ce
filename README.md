# build-ce

future me: FK... THIS PROJECT IS SO MESSY WTF... im tempted to uninstall all the build tools then reinstall them, just so that i can know the exact dependecy or the compile tool BUT FK THAT WILL TAKE TIMES SO NO!

dependencies:
- lazarus 2.2.2 x64
- lazarus 2.2.2 x86 cross-compile
- Microsoft Build tools 2022
- Visual Studio Code 2019
- .NET Framework 4.6.1 targeting pack
- .NET Framework 4.0 targeting pack
- MSVC v143 - VS 2022 C++ x64/x86 build tools (v14.30-17.0)

here are some of extra features with its dependencies

extras:
- speedhack.lpr (required: lazarus)
- luaclient.lpr (required: lazarus)
- DirectXMess.sln (required: msbuild, MSVC v140)
- DotNetcompiler.sln (required: msbuild, .NET Framework)
- monodatacollector.sln (required: msbuild, MSVC v143)
- dotnetdatacollector.sln (required: msbuild, MSVC v143)
- dotnetinvasivedatacollector.sln
- cejvmti.sln
- tcclib.sln (required: msbuild, MSVC v142, MSVC v141, Windows 10 SDK)
- vehdebug.lpr
- dbkkernel.sln

steps:
1. download lazarus
2. install lazarus
3. download msbuild
4. install msbuild
5. install `.NET Framework 4.6.1 targeting pack`
6. install `MSVC v143 - VS 2022 C++ x64/x86 build tools (v14.30-17.0)`
7.  
