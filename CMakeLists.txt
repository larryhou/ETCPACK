cmake_minimum_required (VERSION 3.6)
project(etcpack)

include_directories(source)

file(GLOB SOURCES "source/*.cxx")

set(EXECUTABLE_OUTPUT_PATH "/usr/local/bin")
add_executable( etcpack ${SOURCES} )
