cmake_minimum_required(VERSION 3.23)
project(matchGame)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(matchGame
        match_functions.cpp
        match_functions.h
        match_main.cpp)
