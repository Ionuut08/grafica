cmake_minimum_required(VERSION 3.17)
project(Tema2_grafica)

set(CMAKE_CXX_STANDARD 20)

add_executable(Tema2_grafica main.cpp)
target_link_libraries(Tema2_grafica -lOpenGL32 -lfreeGLUT)