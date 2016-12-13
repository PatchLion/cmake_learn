cmake_minimum_required(VERSION 3.0)

PROJECT(HelloCMake)

SET(SRC_LIST main.cpp)

ADD_EXECUTABLE(HelloCMake ${SRC_LIST})

SET(EXECUTABLE_OUTPUT_PATH ../../bin)
