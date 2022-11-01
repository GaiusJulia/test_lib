cmake_minimum_required(VERSION 3.7.0 FATAL_ERROR)

add_executable(eigenProject main.cpp)

target_include_directories(eigenProject PRIVATE ./)

target_include_directories(eigenProject PRIVATE ./extern/Eigen)

target_compile_features(eigenProject PUBLIC cxx_std_17)