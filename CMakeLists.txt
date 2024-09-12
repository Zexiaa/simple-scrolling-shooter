cmake_minimum_required(VERSION 3.17)

project(Plane VERSION 1.0)

find_package(SDL2 REQUIRED)
find_package(OpenGL REQUIRED)

add_executable(Plane src/main.cpp)

target_link_libraries(Plane PRIVATE SDL2::SDL2)