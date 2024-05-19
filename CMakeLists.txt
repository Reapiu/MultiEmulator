cmake_minimum_required(VERSION 3.10)
project(memu)

set(CMAKE_C_STANDARD 11)
set(CMAKE_C_STANDARD_REQUIRED ON)

file(GLOB_RECURSE SOURCES ${CMAKE_SOURCE_DIR}/source/*.c)

add_executable(memu ${SOURCES})