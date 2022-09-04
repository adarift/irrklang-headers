cmake_minimum_required(VERSION 3.0.0)

project(irrKlang CXX)

add_library(irrKlang INTERFACE)

target_include_directories(irrKlang INTERFACE 
  inc/
)

target_link_libraries(irrKlang INTERFACE
  ${CMAKE_CURRENT_LIST_DIR}/lib/irrKlang.lib
)
