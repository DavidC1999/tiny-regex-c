cmake_minimum_required(VERSION 3.22)
project(tiny_regex_c C)

set(CMAKE_C_STANDARD 17)

add_library(tiny_regex_c ${CMAKE_CURRENT_LIST_DIR}/re.c)
target_include_directories(tiny_regex_c PUBLIC ${CMAKE_CURRENT_LIST_DIR}/include)

