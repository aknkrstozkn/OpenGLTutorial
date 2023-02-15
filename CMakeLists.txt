cmake_minimum_required(VERSION 3.25)
project(OpenGLTutorial)

set(CMAKE_CXX_STANDARD 20)

add_executable(OpenGLTutorial main.cpp)
find_package(GLEW REQUIRED)
target_link_libraries(OpenGLTutorial PRIVATE GLEW::GLEW)