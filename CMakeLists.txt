cmake_minimum_required(VERSION 3.16)

project(Elektrobit VERSION 1.0.0)

add_library(
    helloShared.cpp SHARED
)

add_executable(Elektrobit main.cpp)