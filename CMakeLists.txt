cmake_minimum_required (VERSION 2.6)

project (tp3)

add_executable(tp3 main.cpp Matrix.cpp)

set(CMAKE_C_COMPILER mpicc)
set(CMAKE_CXX_COMPILER mpicxx)

INCLUDE(CPack)
