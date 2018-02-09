cmake_minimum_required(VERSION 3.8)
project(hypothetic_server)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp)
add_executable(hypothetic_server ${SOURCE_FILES})