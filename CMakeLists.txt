cmake_minimum_required(VERSION 3.0)

project(outputPrinter)

include_directories(include)
include_directories(src)

set(SOURCE_FILES
    src/outputPrinter.cpp
)

# Actual project
add_library(outputPrinter ${SOURCE_FILES})
