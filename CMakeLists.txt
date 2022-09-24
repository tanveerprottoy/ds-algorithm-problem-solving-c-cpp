cmake_minimum_required(VERSION 3.13)  # CMake version check
project(AlgorithmsDS)
set(CMAKE_CXX_STANDARD 14)            # Enable c++14 standard

# Add main.cpp file of project root directory as source file
set(SOURCE_FILES prime.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(AlgorithmsDS ${SOURCE_FILES})

# set build folder to bin
set_target_properties(AlgorithmsDS PROPERTIES RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}/bin")