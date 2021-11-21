cmake_minimum_required(VERSION 3.7)

project(myapp)

set( SOURCES
  source/main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})

install (TARGETS ${PROJECT_NAME} RUNTIME DESTINATION bin)
