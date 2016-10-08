cmake_minimum_required(VERSION 3.6)
project(PathFinder)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES "examples/cities.cpp" "examples/image.cpp" "src/AStar.cpp" "src/Dijkstra.cpp" "src/Node.cpp" "src/PathAlgorithm.h" "src/PathFinder.h")
add_executable(PahtFinder ${SOURCE_FILES})