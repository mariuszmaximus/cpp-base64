cmake_minimum_required(VERSION 3.0.0)
project(cpp-base64 VERSION 0.1.0)


add_library(cpp-base64 base64.cpp)

add_executable(base64-test test.cpp)
target_link_libraries(base64-test cpp-base64)