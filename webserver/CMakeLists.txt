cmake_minimum_required(VERSION 3.0.0)

project(webserver)

add_subdirectory(buffer)



add_executable(main.cpp buffer)