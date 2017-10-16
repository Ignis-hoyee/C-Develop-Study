cmake_minimum_required(VERSION 3.8)
project(C_Develop_Study)

set(CMAKE_C_STANDARD 99)

set(SOURCE_FILES main.c test.c)
add_executable(C_Develop_Study ${SOURCE_FILES})