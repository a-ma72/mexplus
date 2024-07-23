cmake_minimum_required( VERSION 3.14 )
set( CMAKE_VERBOSE_MAKEFILE OFF )

add_library(mexplus INTERFACE)
target_include_directories(mexplus PUBLIC include $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>)