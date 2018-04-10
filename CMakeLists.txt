cmake_minimum_required(VERSION 3.10)
project(goim_cpp)

set(CMAKE_CXX_STANDARD 17)

set(SolutionDir ${PROJECT_SOURCE_DIR})

if (CMAKE_BUILD_TYPE STREQUAL "Debug")
    set(FlowOutPutDir ${PROJECT_SOURCE_DIR}/bin/debug)
else ()
    set(FlowOutPutDir ${PROJECT_SOURCE_DIR}/bin/release)
endif ()

set(CMAKE_MODULE_PATH "${CMAKE_CURRENT_SOURCE_DIR}/cmake" ${CMAKE_MODULE_PATH})

include(functions)

add_subdirectory(libs)
add_subdirectory(comet)
add_subdirectory(logic)
add_subdirectory(router)