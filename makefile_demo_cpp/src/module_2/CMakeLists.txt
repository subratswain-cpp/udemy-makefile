cmake_minimum_required(VERSION 3.30)
project(mod2)

add_library(mod2 SHARED mod2.cpp)

add_executable(mod2_exe test_mod2.cpp)

target_link_libraries(mod2_exe mod2)
