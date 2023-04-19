project(test_app C)
cmake_minimum_required(VERSION 2.6.3)

add_executable (app app.c)

install(TARGETS app DESTINATION ${CMAKE_INSTALL_PREFIX}/bin)

