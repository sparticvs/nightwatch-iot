cmake_minimum_required(VERSION 3.37)
project(nightwatch)

set(CMAKE_SYSTEM_PROCESSOR arm)
set(CMAKE_C_COMPILER )

add_executable(nightwatch_fw
    main.c
)
