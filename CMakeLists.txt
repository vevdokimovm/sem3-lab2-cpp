cmake_minimum_required(VERSION 3.17)
project(sem3_lab2)

set(CMAKE_CXX_STANDARD 14)

add_executable(sem3_lab2 ArraySequence.hpp BST.hpp Dictionary.hpp DynamicArray.hpp Histogram.hpp Interface.hpp
        main.cpp LinkedList.hpp ListSequence.hpp Sorts.hpp SearchOftenSub.hpp Sequence.hpp SortedSequence.hpp
               Sparce_vector.hpp testBST.hpp testDictionary.hpp testHistogram.hpp testSearchOftenSub.hpp
        testSortedSeq.hpp testSorts.hpp testSparceVector.hpp)