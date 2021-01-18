cmake_minimum_required(VERSION 3.1)

project(test-cmake)

add_executable(main main.cpp)
target_compile_features(main PUBLIC cxx_std_17)
