cmake_minimum_required(VERSION 3.5)
project(leeetcodeCPP)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp 082/Solution.cpp 082/ListNode.cpp 082/ListNode.h)
add_executable(leeetcodeCPP ${SOURCE_FILES})