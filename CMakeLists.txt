cmake_minimum_required(VERSION 3.26)
project(DES C)

set(CMAKE_C_STANDARD 11)

add_executable(DES cipher.c tables.h)
