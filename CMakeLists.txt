# CMakeList.txt : CMake project for CMakeExample, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("CMakeWSL2SDL2Test")

find_package(SDL2 REQUIRED)
include_directories(${SDL2_INCLUDE_DIRS})

# Add source to this project's executable.
add_executable (CMakeWSL2SDL2Test "main.cpp")
target_link_libraries(CMakeWSL2SDL2Test ${SDL2_LIBRARIES})
# TODO: Add tests and install targets if needed.
