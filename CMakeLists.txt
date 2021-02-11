cmake_minimum_required(VERSION 3.4)
project(doctest-bug CXX)

set(CMAKE_BUILD_TYPE Release)

enable_testing()

add_executable(hangs hangs.cpp)
add_test(NAME hangs COMMAND hangs)
