cmake_minimum_required(VERSION 3.28)
project(demo2)

set(CMAKE_CXX_STANDARD 20)

add_executable(demo2)
target_sources(
        demo2
        PRIVATE main.cpp
        PRIVATE FILE_SET CXX_MODULES FILES module.cppm)