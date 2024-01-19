# CMakeLists.txt

cmake_minimum_required(VERSION 3.12)  # Specify the minimum version of CMake required

# Project name and version
project(MyProject VERSION 1.0)

# Set C++ standard
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Add the executable
add_executable(my_executable main.cpp)

