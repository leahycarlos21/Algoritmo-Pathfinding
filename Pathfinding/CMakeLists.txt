cmake_minimum_required(VERSION 3.10)
project(Pathfinding)

set(CMAKE_CXX_STANDARD 14)

add_executable(Pathfinding main.cpp "Algoritmo AStar/AStarSearch.h" "Algoritmo AStar/MapSearchNode.cpp" "Algoritmo AStar/MapSearchNode.h" "Algoritmo AStar/execAStar.cpp" "Algoritmo AStar/execAStar.h" globalArray.cpp globalArray.h coordinate.h)