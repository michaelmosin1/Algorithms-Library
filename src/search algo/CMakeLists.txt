cmake_minimum_required(VERSION 3.8)
enable_language(C)
add_library(searchalgo SHARED searchalgo.c)
target_compile_options(sorting PUBLIC "-O2")
