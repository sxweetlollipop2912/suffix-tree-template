cmake_minimum_required(VERSION 3.21)
project(my_suffix_tree)

set(CMAKE_CXX_STANDARD 11)

add_executable(my_suffix_tree main.cpp SuffixTree/SuffixEdge.h SuffixTree/SuffixNode.h SuffixTree/SuffixTree.h SuffixTree/KeyInternal.h SuffixTree.h)
