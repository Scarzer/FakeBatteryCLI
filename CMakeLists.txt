cmake_minimum_required(VERSION 3.5)
project(myFakeBattery)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

include_directories(./include)
# Specific to Arch. Ubuntu places headers in a different location
set(SOURCE_FILES main.cpp )
add_executable(myFakeBattery ${SOURCE_FILES} main.cpp)