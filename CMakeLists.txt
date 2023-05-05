project(HelloWorldCpp)
cmake_minimum_required(VERSION 3.22)

add_executable(hello-world-cpp main.cpp)
install(TARGETS hello-world-cpp DESTINATION bin)
