set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

cmake_minimum_required(VERSION 3.29)
project(HelloWorld LANGUAGES C VERSION 1.0)
add_executable(hello)
target_sources(hello
  PRIVATE
    src/hello.c
)
