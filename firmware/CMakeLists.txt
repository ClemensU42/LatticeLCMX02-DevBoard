
cmake_minimum_required(VERSION 3.18)

project(LatticeLCMX02-DevBoard)

add_executable(LatticeLCMX02-DevBoard src/main.c)

target_include_directories(LatticeLCMX02-DevBoard PRIVATE include)

