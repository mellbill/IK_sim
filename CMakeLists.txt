cmake_minimum_required(VERSION 3.20)

project(IKSimulator)

set(CMAKE_CXX_STANDARD 17)

include_directories(include)

add_executable(
    ik_sim

    src/main.cpp
    src/renderer.cpp
)