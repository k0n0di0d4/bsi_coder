cmake_minimum_required(VERSION 3.17)
project(bsi_coder)

set(CMAKE_CXX_STANDARD 14)

add_executable(bsi_coder main.cpp algorithms/aes/AES.cpp algorithms/aes/AES.h algorithms/aes/aes_test.cpp algorithms/aes/aes_test.h)