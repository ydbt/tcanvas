cmake_minimum_required(VERSION 3.17)
project(sdtp)

set(CMAKE_CXX_STANDARD 11)
include_directories("." "./include" "E:\\DevTool\\Catch2\\include")
file(GLOB_RECURSE  qntp src/*.cpp)
set(SOURCE_FILES ${qntp} )
add_executable(${PROJECT_NAME} ${SOURCE_FILES})
