# CMakeLists.txt
cmake_minimum_required(VERSION 3.0)
project(test)

# main target
add_executable(main)
target_sources(main PRIVATE src/main.cpp)
set_property(TARGET main PROPERTY CXX_STANDARD 20)