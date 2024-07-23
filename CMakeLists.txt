cmake_minimum_required(VERSION 3.20)
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(subprocess)

add_library(subprocess INTERFACE)

target_include_directories(subprocess INTERFACE include/)
