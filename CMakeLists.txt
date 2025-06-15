cmake_minimum_required(VERSION 3.20)
project(TemplateCpp20Project)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(3rdparty)
add_subdirectory(src)
