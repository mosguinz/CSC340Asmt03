cmake_minimum_required(VERSION 3.21)
project(CSC340Asmt03)

set(CMAKE_CXX_STANDARD 20)

add_executable(part_c Assignment-03_PC_Dictionary.cpp Dictionary.cpp Dictionary.h DictEntry.cpp DictEntry.h DictClient.cpp DictClient.h QueryArg.cpp QueryArg.h)