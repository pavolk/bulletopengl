cmake_minimum_required(VERSION 3.10)

project(bulletopengl)

include(${CMAKE_CURRENT_BINARY_DIR}/conanbuildinfo.cmake)

conan_basic_setup(TARGETS)

add_subdirectory(application)
