# version
cmake_minimum_required(VERSION 2.8)

# project name and language
project(test_cmake CXX)

# Create 'a.out' from 'main.cpp' and 'hello.cpp'
add_executable(a.out main.cpp hello.cpp)

