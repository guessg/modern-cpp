cmake_minimum_required(VERSION 3.28)
project(demo1)

set(CMAKE_CXX_STANDARD 20)

add_executable(demo1)
target_sources(
        demo1
        PRIVATE main.cpp)