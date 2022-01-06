# CMakeWSL2SDL2Example
Example for VS2022

Taken and modified from https://trenki2.github.io/blog/2017/06/02/using-sdl2-with-cmake/

# Uses
1. SDL2-2.0.18
2. Visual Studio 2022
3. CMake 3.8


Tutorial 

Follow guide written from above
Changes required

Convert VS project to use CMakePresets.json
Inside CMakePresets.json
find cacheVariables{} and append ```"SDL2_DIR": "<PATH TO>/SDL2-2.0.18"``` to configurations that require it



