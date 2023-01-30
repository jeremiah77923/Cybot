cmake_minimum_required(VERSION 3.24)
project(selfdrivingcar)

set(CMAKE_CXX_STANDARD 17)

add_executable(selfdrivingcar main.cpp image.cpp image.h left.cpp left.h right.cpp right.h forward.cpp forward.h backwards.cpp backwards.h)
