cmake_minimum_required(VERSION 3.28)
project(WurstbudeEngine)

set(CMAKE_CXX_STANDARD 23)

add_library(WurstbudeEngine SHARED library.cpp)

#set_target_properties(WurstbudeEngine PROPERTIES
#        ARCHIVE_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}"  #.lib
#        RUNTIME_OUTPUT_DIRECTORY "${CMAKE_BINARY_DIR}" #.dll
#)