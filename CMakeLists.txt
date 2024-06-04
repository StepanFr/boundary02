cmake_minimum_required(VERSION 3.5)
project(Cpp-Software-Design)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

get_cmake_property(_variableNames VARIABLES)
list (SORT _variableNames)
foreach (_variableName ${_variableNames})
    message(STATUS "${_variableName}=${${_variableName}}")
endforeach()

set(SOURCES
    Main.cpp
)

add_executable(Cpp-Software-Design ${SOURCES})


