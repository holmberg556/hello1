cmake_minimum_required(VERSION 3.14.5)
project(hello1)

add_subdirectory(subdir)

add_executable(hello_world hello.cpp)
target_link_libraries(hello_world PUBLIC world)
