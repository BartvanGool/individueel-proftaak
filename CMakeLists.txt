cmake_minimum_required(VERSION 3.5)


include($ENV{ADF_PATH}/CMakeLists.txt)
include($ENV{IDF_PATH}/tools/cmake/project.cmake)
set(EXTRA_COMPONENT_DIRS ${CMAKE_SOURCE_DIR}/components/)
set(EXTRA_COMPONENT_DIRS $ENV{IDF_PATH}/examples/common_components/protocol_examples_common)
set(EXTRA_COMPONENT_DIRS $ENV{ADF_PATH}/components)

project(IMC-indiv-bartvangool)