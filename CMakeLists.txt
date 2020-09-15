cmake_minimum_required(VERSION 3.14 FATAL_ERROR)

project(SMM2CourseDecryptor)

add_executable(${PROJECT_NAME} main.c aes.c aes.h keys.h)
target_include_directories(${PROJECT_NAME} PUBLIC ${CMAKE_CURRENT_LIST_DIR})

