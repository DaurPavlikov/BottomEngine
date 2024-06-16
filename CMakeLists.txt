cmake_minimum_required(VERSION 3.0)

project(bottomengine)

add_executable(bottomengine main.cpp)

install(TARGETS bottomengine RUNTIME DESTINATION bin)
