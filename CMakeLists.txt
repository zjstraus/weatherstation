# The following lines of boilerplate have to be in your project's CMakeLists
# in this exact order for cmake to work correctly
cmake_minimum_required(VERSION 3.16)

set(EXTRA_COMPONENT_DIRS ${CMAKE_CURRENT_SOURCE_DIR}/../esp-idf-drivers/components)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(i2c-simple)
