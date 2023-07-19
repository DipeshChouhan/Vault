cmake_minimum_required(VERSION 3.27)
project(vault)

set(CMAKE_C_STANDARD 11)

set(SOURCE_DIR src)

list(APPEND SOURCE_FILES ${SOURCE_DIR}/main.c ${SOURCE_DIR}/vault.c ${SOURCE_DIR}/vault.h)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})
