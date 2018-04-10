file(GLOB COMET_ROOT_HPP *.hpp)
file(GLOB COMET_ROOT_CPP *.cpp)

set(APP_NAME "comet")

add_executable(${APP_NAME} ${COMET_ROOT_HPP} ${COMET_ROOT_CPP})