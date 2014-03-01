cmake_minimum_required(VERSION 2.8)
project(MultipleWindowsGL)

find_package(GLUT REQUIRED)
include_directories(${GLUT_INCLUDE_DIR})

add_executable(test main.cpp)
target_link_libraries(test ${GLUT_LIBRARIES})