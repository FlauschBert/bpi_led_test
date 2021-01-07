cmake_minimum_required(VERSION 3.7)

project(led_test)

add_subdirectory(wiringPi)

add_executable(led_test main.cpp)
target_link_libraries(led_test wiringPi)
