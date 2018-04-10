file(GLOB ROUTER_ROOT_HPP *.hpp)
file(GLOB ROUTER_ROOT_CPP *.cpp)

set(APP_NAME "router")

add_executable(${APP_NAME} ${ROUTER_ROOT_HPP} ${ROUTER_ROOT_CPP})