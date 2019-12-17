cmake_minimum_required(VERSION 3.10)
project(stribog)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(stribog gost_3411_2012_calc.c stribog.c)