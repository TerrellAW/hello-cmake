cmake_minimum_required(VERSION 4.3.0)
project(hello-cmake)

set(SOURCE_DIR src)
set(SOURCE_FILES ${SOURCE_DIR}/hello.cpp)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})
