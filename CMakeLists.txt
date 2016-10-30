# Minimum version for CMake
cmake_minimum_required(VERSION 2.8)

# Project config
project(sicpp)

# Bring headers
include_directories(include)

# Bring sources
file(GLOB SOURCES "src/sicpp/*.cpp")

add_executable(sicpp ${SOURCES})
