cmake_minimum_required(VERSION 3.25)
project(AymDroid)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(third_party)

add_executable(AymDroid main.cpp)

target_link_libraries(AymDroid botcraft)