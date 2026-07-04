cmake_minimum_required(VERSION 4.3)
project(blu_internal)

set(CMAKE_CXX_STANDARD 23)

add_library(blu_internal SHARED src/library.cpp)
