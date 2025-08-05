cmake_minimum_required(VERSION 3.24.0)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED true)

project(template)

include_directories(${CMAKE_CURRENT_LIST_DIR}/src)
add_executable(${PROJECT_NAME} ./src/main.cpp)