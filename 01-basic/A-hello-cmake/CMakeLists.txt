# Set the minimum version of CMake that can be used
# To find the cmake version run
# $ cmake --version
cmake_minimum_required(VERSION 3.5)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

# Set the project name
project (hello_cmake)

# Add an executable
# add_executable(hello_cmake main.cpp)
add_executable(${PROJECT_NAME} main.cpp)
