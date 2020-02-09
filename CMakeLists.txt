cmake_minimum_required(VERSION 3.13)

add_executable(bgen generators/bgen.cpp)
add_executable(gen-bipartite-graph generators/gen-bipartite-graph.cpp)
add_executable(gen-rooted-tree-graph generators/gen-rooted-tree-graph.cpp)
add_executable(gen-tree-graph generators/gen-tree-graph.cpp)
add_executable(igen generators/igen.cpp)
add_executable(iwgen generators/iwgen.cpp)
add_executable(multigen generators/multigen.cpp)
add_executable(sgen generators/sgen.cpp)
add_executable(swgen generators/swgen.cpp)

include_directories(.)