 cmake_minimum_required(VERSION 3.30)

project(OdfReader VERSION 0.1.0 LANGUAGES C CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(PROJECT_SOURCE_DIR src)

add_executable(OdfReader
 src/main.cpp
)
