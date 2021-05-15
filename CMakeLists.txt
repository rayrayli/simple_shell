cmake_minimum_required(VERSION 3.15)
project(sish C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(sish
    sish.c
    sish.h
        parse.c
        execute.c
        task.c)
