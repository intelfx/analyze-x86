cmake_minimum_required(VERSION 3.28)
project(analyze-x86)
set(CMAKE_C_STANDARD 99)

add_executable(analyze-x86 analyze-x86.c)
target_include_directories(analyze-x86 PRIVATE ${CMAKE_SOURCE_DIR}/include)
