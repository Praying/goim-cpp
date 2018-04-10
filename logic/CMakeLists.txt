file(GLOB LOGIC_ROOT_HPP *.hpp)
file(GLOB LOGIC_ROOT_CPP *.cpp)

set(APP_NAME "logic")

add_executable(${APP_NAME} ${LOGIC_ROOT_HPP} ${LOGIC_ROOT_CPP})