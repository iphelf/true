cmake_minimum_required(VERSION 3.0 FATAL_ERROR)

project(true LANGUAGES C CXX)

set(CMAKE_AUTOUIC OFF)
set(CMAKE_AUTOMOC OFF)
set(CMAKE_AUTORCC OFF)

add_executable(true src/main.cpp)
