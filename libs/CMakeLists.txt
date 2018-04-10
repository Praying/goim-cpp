auto_sources(LIBS_HPP "*.hpp" "RECURSE" "${CMAKE_CURRENT_SOURCE_DIR}")
auto_sources(LIBS_CPP "*.cpp" "RECURSE" "${CMAKE_CURRENT_SOURCE_DIR}")

set(LIBS_NAME "goimcpplibs")
add_library(${LIBS_NAME} ${LIBS_HPP} ${LIBS_CPP})