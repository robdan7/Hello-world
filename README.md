# Hello-world
## How to play Hello world in CLion
- Install Msys64: https://www.msys2.org/
- In Msys64, run the following script `pacman -S mingw-w64-x86_64-gdb mingw-w64-x86_64-gcc mingw-w64-x86_64-cmake mingw-w64-x86_64-make`
- Download this repository while you wait.
- Once Msys is done, open CLion. Open the repository from source, select use existing CMake project.
- Go to settings->Build, Execution, Deployment->Toolchains. Click on the plus sign and choose MinGW
- In Environment, press ... and choose the mingw64 folder within msys64. Compiler, debugger etc should be automagically detected.
- Still within the Build menu, go to CMake and add a build config. Set the build type to Release and press the tiny up arrow, next to the + sign, to set it as default.
- Click OK. You should now be able to compile and run the program by pressing the green arrow in the upper right corner :)
