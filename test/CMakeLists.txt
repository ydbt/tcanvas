include_directories("." "./include" "E:\\DevTool\\Catch2\\include")

file(GLOB_RECURSE  qntp src/*.cpp)
file(GLOB_RECURSE  qntp test/*.cpp)
list(REMOVE_ITEM qntp "src/main.cpp")


set(SOURCE_FILES ${qntp} )

add_executable(MyTest src/main.cpp)

