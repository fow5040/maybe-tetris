cmake_minimum_required(VERSION 3.8)
project(maybe_tetris)
set(CMAKE_CXX_STANDARD 14) # Try 11 if your compiler does not support C++14
set(SOURCE_FILES src/main.cpp)
set(CMAKE_CXX_FLAGS "-lncurses")
add_executable(maybe_tetris ${SOURCE_FILES})
