 cmake_minimum_required(VERSION 3.0)
project(Solder)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_BUILD_TYPE Debug)
include_directories(include())
add_executable(main_cmake main.cpp src/gun.cpp src/solder.cpp)
 