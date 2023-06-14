cmake_minimum_required(VERSION 3.24)
project(dummy-3rds)

add_subdirectory(llhttp)

add_library(dummy-3rds main.cpp)
