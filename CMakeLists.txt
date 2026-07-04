cmake_minimum_required(VERSION 3.33)
project(blu_internal)

set(CMAKE_CXX_STANDARD 23)

find_package(imgui CONFIG REQUIRED)

add_library(blu_internal SHARED src/library.cpp)

target_link_libraries(blu_internal PRIVATE
        imgui::imgui
)