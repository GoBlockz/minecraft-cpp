cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(MinecraftCpp)

find_package(OpenGL REQUIRED)
find_package(GLM REQUIRED)
find_package(glfw3 REQUIRED)

add_executable(minecraft main.cpp)
target_link_libraries(minecraft OpenGL::GL glfw glm)