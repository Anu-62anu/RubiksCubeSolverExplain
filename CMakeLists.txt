cmake_minimum_required(VERSION 3.28)
project(RubiksCubeSolverExplain)

set(CMAKE_CXX_STANDARD 17)

add_executable(RubiksCubeSolverExplain main.cpp
        GenericRubiksCube.cpp
        GenericRubiksCube.h)
