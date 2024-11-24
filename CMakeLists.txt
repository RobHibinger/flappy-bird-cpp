cmake_minimum_required(VERSION 3.5.0)

project(FlappyBird VERSION 0.1.0 LANGUAGES C CXX)

add_executable(FlappyBird src/main.cpp)

find_package(raylib CONFIG REQUIRED)
target_link_libraries(FlappyBird PRIVATE raylib)