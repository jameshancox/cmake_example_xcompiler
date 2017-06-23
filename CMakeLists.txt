cmake_minimum_required (VERSION 3.9)
project (example_project CUDA CXX)

set(CMAKE_CUDA_FLAGS "-lineinfo -Xcompiler=/bigobj")

add_library(example_library SHARED example_library/example.cu)