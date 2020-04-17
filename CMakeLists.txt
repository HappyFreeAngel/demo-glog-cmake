cmake_minimum_required(VERSION 3.5 FATAL_ERROR)
project(proj   LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

find_package (glog)

add_executable(demo01 1.cpp)
target_link_libraries (demo01 glog)

