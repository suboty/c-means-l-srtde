cmake_minimum_required(VERSION 4.0)
project(c_means_l_srtde)

set(CMAKE_CXX_STANDARD 14)

include_directories(/opt/homebrew/include)
link_directories(/opt/homebrew/lib)

add_executable(${PROJECT_NAME} src/main.cpp)