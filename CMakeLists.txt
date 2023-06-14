cmake_minimum_required(VERSION 3.24)
project(dummy-3rds)

if (NOT BUILD_SHARED_LIBS)
    set (BUILD_SHARED_LIBS FALSE CACHE BOOL "")
    set (BUILD_STATIC_LIBS TRUE CACHE BOOL "")
endif()
add_subdirectory(llhttp)

add_library(dummy-3rds main.cpp)
