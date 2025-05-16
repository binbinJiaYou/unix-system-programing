cmake_minimum_required(VERSION 3.10.0)
project(unix-system-programing VERSION 0.1.0 LANGUAGES C CXX)

# 使用 gnu17 标准
set(CMAKE_C_STANDARD 17)
set(CMAKE_C_EXTENSIONS ON)
set(CMAKE_C_STANDARD_REQUIRED ON)
# 使用 gnu++17 标准
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_EXTENSIONS ON)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(unix-system-programing main.cpp)

