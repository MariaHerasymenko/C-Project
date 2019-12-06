cmake_minimum_required(VERSION 3.14)
project(rational_gerasimenko C)

set(CMAKE_C_STANDARD 99)

add_executable(rational_gerasimenko src/rational_gerasimenko.c headers/rational_gerasimenko.h headers/common.h tests/rational_gerasimenko_test.c)
