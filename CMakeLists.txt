cmake_minimum_required(VERSION 3.12)
project(rbtree)

set(CMAKE_CXX_STANDARD 14)

add_executable(rbtree src/main.cpp include/tree.h)