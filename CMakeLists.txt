cmake_minimum_required(VERSION 3.17)

project(BusquedaProfundidad)

add_executable(BusquedaProfundidad glad/glad.c main.cpp)

target_link_libraries(BusquedaProfundidad GL dl glfw)
