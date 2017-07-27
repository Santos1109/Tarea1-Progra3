cmake_minimum_required(VERSION 3.7)
project(HW)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.cpp Evaluador.h)
add_executable(HW ${SOURCE_FILES})