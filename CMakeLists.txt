cmake_minimum_required(VERSION 3.6)
project(redis_3_0_annotated)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(redis_3_0_annotated ${SOURCE_FILES})