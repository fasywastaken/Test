cmake_minimum_required(VERSION 4.0)
project(test)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(test
        test/main.cpp
        test/main.h)
