cmake_minimum_required(VERSION 3.8)
project("thread_pool")

set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin) #dll path
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib) #lib path

add_executable("thread_pool" example.cpp)