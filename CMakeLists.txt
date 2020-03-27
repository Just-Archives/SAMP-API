cmake_minimum_required(VERSION 3.8)

project(sampapi VERSION 1.0.0 LANGUAGES CXX)

add_library(sampapi STATIC)
target_include_directories(sampapi PRIVATE "sampapi/src/common")

add_subdirectory("sampapi/src/")
