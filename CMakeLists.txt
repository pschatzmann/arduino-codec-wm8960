cmake_minimum_required(VERSION 3.16)

# set the project name
project(arduino-wm8960)

set(CMAKE_CXX_STANDARD 17)

# define libraries
add_library (arduino-wm8960 mtb_wm8960.cpp)

# define location for header files
target_include_directories(arduino-wm8960 PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/src )
