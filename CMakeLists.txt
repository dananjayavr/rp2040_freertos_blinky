cmake_minimum_required(VERSION 3.12)

include(pico_sdk_import.cmake)

project(freertos_blinky)

pico_sdk_init()

add_subdirectory(freertos)
add_subdirectory(ProjectFiles)