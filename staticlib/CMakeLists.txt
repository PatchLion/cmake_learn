cmake_minimum_required(VERSION 3.0)

PROJECT(Static)

SET(SRC_LIST static.cpp)

ADD_LIBRARY(static SHARED ${SRC_LIST})

SET(LIBRARY_OUTPUT_PATH ../../lib)