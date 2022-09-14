cmake_minimum_required(VERSION 3.20.0 FATAL_ERROR) # Maybe we can reduce this?

project(
    VulkanMemoryAllocator-Hpp
    VERSION 0
    DESCRIPTION "C++ bindings for the VulkanMemoryAllocator library."
    LANGUAGES C CXX)

add_library(VulkanMemoryAllocator-Hpp INTERFACE)
target_include_directories(VulkanMemoryAllocator-Hpp INTERFACE include)
