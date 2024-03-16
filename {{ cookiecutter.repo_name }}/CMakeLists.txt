cmake_minimum_required(VERSION 3.10)

project(MCTS_implementation VERSION 1.0)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED True)

# Specify the include directories
include_directories(/opt/homebrew/include/eigen3)
include_directories(/opt/homebrew/include)

# Set the output folder where your program will be created
set(CMAKE_BINARY_DIR ${CMAKE_SOURCE_DIR}/bin)
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_BINARY_DIR})
set(LIBRARY_OUTPUT_PATH ${CMAKE_BINARY_DIR})

# The following folder will be included
include_directories("${PROJECT_SOURCE_DIR}" "${PROJECT_SOURCE_DIR}/src")

# Add files to compile
file(GLOB SOURCES "*.cpp" ".hpp" "src/*.hpp" "src/*.cpp")
add_executable(${PROJECT_NAME} ${SOURCES})
