cmake_minimum_required(VERSION 3.4)
project(doctest-bug CXX)

add_executable(hangs hangs.cpp)
add_test(NAME hangs COMMAND hangs)
