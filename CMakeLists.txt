cmake_minimum_required(VERSION 3.15)

project(MultiCoreBenchmarkPlatform
        VERSION 1.0
        DESCRIPTION "A cross-platform benchmarking system for multi-core CPU performance"
        LANGUAGES C CXX)

# Global C++ standard
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Enable verbose build output
set(CMAKE_VERBOSE_MAKEFILE ON)

# Add subdirectories
add_subdirectory(cpp)
"" 
