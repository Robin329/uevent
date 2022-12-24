cmake_minimum_required(VERSION 3.14)
project(uevent)

set(CMAKE_CXX_STANDARD 17)

add_executable(uevent uevent.cpp uevent.h uevents.c)