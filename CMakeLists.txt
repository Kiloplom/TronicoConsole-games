# ArcadeGamesProject/CMakeLists.txt
cmake_minimum_required(VERSION 3.10)

project(ArcadeGamesProject C)

set(CMAKE_C_STANDARD 99)

# Include header files directory
include_directories(${CMAKE_SOURCE_DIR}/include)

# Add the source files
add_executable(ArcadeGamesProject src/main.c)

# Link libraries if necessary (e.g., m for math)
# target_link_libraries(ArcadeGamesProject m)
