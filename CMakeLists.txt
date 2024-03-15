cmake_minimum_required(VERSION 3.16)
project("vulkanproject" CXX)
add_compile_options(-std=c++17)

add_executable(vulkantest main.cpp)
target_link_libraries(vulkantest vulkan glfw)
#target_link_libraries(vulkantest vulkan glfw ${GL_LIBRARY})
