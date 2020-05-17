cmake_minimum_required(VERSION 3.16)
project(MyVulkanTutorial)

set(CMAKE_CXX_STANDARD 20)

find_package(Vulkan REQUIRED)
find_package(glfw3 REQUIRED)

add_executable(MyVulkanTutorial main.cpp)

target_link_libraries(MyVulkanTutorial glfw vulkan)