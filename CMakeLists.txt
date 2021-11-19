cmake_minimum_required(VERSION 3.0)
project(PI)

set(CMAKE_C_COMPILER gcc)
set(CMAKE_C_STANDARD 99)

add_executable(test ./src/test.c)