cmake_minimum_required(VERSION 3.0)

project(hellow)

add_executable(hellow main.cpp)

install(TARGETS hellow RUNTIME DESTINATION bin)
