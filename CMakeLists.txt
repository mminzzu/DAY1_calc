cmake_minimum_required(VERSION 3.10)
project(Calculator C)
include_directories(.)
add_executable(prog cal_main.c add.c sub.c mul.c dur.c)
