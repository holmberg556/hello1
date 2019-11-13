cmake_minimum_required(VERSION 3.14.5)
project(hello1_sub)

add_library(world STATIC world.c)
target_include_directories(world PUBLIC .)

