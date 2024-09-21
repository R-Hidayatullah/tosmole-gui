cmake_minimum_required(VERSION 3.5.0)

# Define the project name and version
project(tosmole-gui VERSION 0.1.0 LANGUAGES C CXX)

# Add the executable target
add_executable(tosmole-gui main.cpp)

# Specify C++17 standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)
