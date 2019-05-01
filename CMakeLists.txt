cmake_minimum_required(VERSION 3.14)
project(Alg_Half_Divide C)

set(CMAKE_C_STANDARD 11)

add_executable(Alg_Half_Divide main.c)
target_link_libraries(Alg_Half_Divide quadmath)