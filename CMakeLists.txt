cmake_minimum_required(VERSION 2.8)

project(QPDemo)

INCLUDE_DIRECTORIES(eigen .)

add_executable(QPDemo uQuadProg++.cc umain.cc EigenQP.cpp)
