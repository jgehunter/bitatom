cmake_minimum_required(VERSION 3.11-3.18)

project(
    BITATOM
    VERSION 0.1
    DESCRIPTION "Small CMake example built with VSCode"
)

include(CTest)

add_subdirectory(hello)
add_subdirectory(apps)
add_subdirectory(tests)