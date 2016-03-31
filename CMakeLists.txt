cmake_minimum_required(VERSION 3.4 FATAL_ERROR)
project(TestProject)
add_executable(TestProject test.cpp)

enable_testing ()

set(TESTS
    base_test.cpp
)
