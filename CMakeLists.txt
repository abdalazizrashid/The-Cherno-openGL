cmake_minimum_required(VERSION 3.15)
project(openGL_learning)

set(CMAKE_CXX_STANDARD 17)

add_executable(openGL_learning main.cpp)
find_package(glfw3 3.3 REQUIRED)
target_link_libraries(openGL_learning glfw)
find_package(OpenGL REQUIRED)
target_link_libraries(openGL_learning GL)

