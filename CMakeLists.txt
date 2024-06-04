cmake_minimum_required(VERSION 3.5)
project(Cpp-Software-Design)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

set(SOURCES
    Main.cpp
    G26_CRTP_2.cpp
)

add_executable(Cpp-Software-Design ${SOURCES})


