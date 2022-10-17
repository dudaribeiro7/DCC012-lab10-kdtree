cmake_minimum_required(VERSION 3.10)

project(kdtree CXX)

enable_testing()
include_directories(kdtree)
add_subdirectory(tests)

add_test(
    NAME teste1
    COMMAND $<TARGET_FILE:test1>
)

add_test(
    NAME teste2
    COMMAND $<TARGET_FILE:test2>
)


