# C++ Compilers
There are few main lines of C++ compilers. Gcc, Clang and MSVC. Also- funny to note, but CLang and gcc are for sure few generations behind in their c++ implementation, for example in 2023, both clang and gcc only FULLY support the c++17...
## GCC
Gcc seems to be the most popular and is available on windows, linux and mac. Probably best one I've used so far. As much as I saw the main issue with gcc is setting up the cross compilation.
### Installation
* Ubuntu/Debian... just use your package manager to install gcc (sudo apt install build-essential for Ubuntu/Debian) and ur good, check if it's available in the PATH.
* On Windows... There are many ways of getting GCC, but most of them suck. Theres MSYS, CYGWIN and a bunch on baloney dogshit utilities that will tell you iTs eAsY tO iNsTaLl. Dont be fooled, what you need is Mingw64 and that's it. Obvioulsly nobody needs the 32bit version cuz its not 1999 anymore. Just get this and if make sure to add the dir to your PATH. [Mingw64 download](https://sourceforge.net/projects/mingw-w64/).
* Mac os. Probably you can use brew package manager to get it
* Linux general- if ur using Arch or some other esoteric shit why are you even reading this, you already should know by now, fuck off.
## Clang
Clang is using LLVM and AFAIK it is the reason LLVM was made in the first place. I don't have too much experience with it but it seems to be pretty good, just used less than gcc for some reason. It also seems like Clang is easier to setup as a cross-compiler.
### Installation
* Just fucking google it idk.
## MSVC
MSVC is kinda dogshit and is only available in Visual Studio (NOT VS Code), so fuck it, no like. My experience with MSVC- It will spit out an exe, but if you want to be able to configue that your project works in ANY cross platform way or to be able to give ur project and dep's to someone else- good fucking luck bro.
### Installation
* You're gonna need to download a fucking Visual studio and then download like 10Gb of shit to make it work. 