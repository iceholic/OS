cmake_minimum_required(VERSION 3.22)
project(OS)

set(CMAKE_CXX_STANDARD 14)

add_executable(OS ostep/cpu.c learn/test.cpp ostep/t0.cpp)
