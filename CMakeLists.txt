set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

cmake_minimum_required(VERSION 3.10)
project(HelloWorld LANGUAGES C VERSION 1.0)
add_executable(hello src/hello.c)
