cmake_minimum_required(VERSION 3.29)
project(git_control)

set(CMAKE_CXX_STANDARD 20)

add_executable(git_control main.cpp
        student.cpp
        student.h)
