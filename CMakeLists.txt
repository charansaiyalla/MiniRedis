cmake_minimum_required(VERSION 3.20)

project(
    MiniRedis
    VERSION 1.0.0
    DESCRIPTION "Educational Redis-like in-memory database"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(
    MiniRedis
    src/main.cpp
)