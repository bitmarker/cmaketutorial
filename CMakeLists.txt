project (cmake-tutorial)

cmake_minimum_required (VERSION 3.0)

set(INSTALL_DIR "${CMAKE_CURRENT_SOURCE_DIR}/dist/${CMAKE_BUILD_TYPE}/bin/")

add_subdirectory(src)
