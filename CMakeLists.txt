cmake_minimum_required(VERSION 2.8.9)
project(HelloWorld)
file(GLOB SOURCES "src/*.cpp")
add_executable(HelloWorld src/main.cpp)