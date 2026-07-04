cmake_minimum_required(VERSION 4.3)
project(blu_external)

set(CMAKE_CXX_STANDARD 23)

add_library(blu_external SHARED src/library.cpp)
