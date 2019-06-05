cmake_minimum_required(VERSION 3.11)
project(BrownianMotion)

set(CMAKE_CXX_STANDARD 14)

find_package(SFML 2.5 COMPONENTS graphics REQUIRED)

add_executable(Test main.cpp)

target_link_libraries(Test sfml-graphics)