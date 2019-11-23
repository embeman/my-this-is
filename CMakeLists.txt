cmake_minimum_required(VERSION 2.6)
project(calculator)

add_executable(calc calc.cpp)
install(TARGETS calc DESTINATION bin)
