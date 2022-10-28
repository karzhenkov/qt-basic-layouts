cmake_minimum_required(VERSION 3.15)

project(basiclayouts LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_AUTOMOC ON)

find_package(Qt5 REQUIRED Widgets)
link_libraries(Qt5::Widgets)

add_executable(basiclayouts
  main.cpp
  dialog.cpp
  dialog.h
)
