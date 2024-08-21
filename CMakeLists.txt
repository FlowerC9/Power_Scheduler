cmake_minimum_required(VERSION 3.10)
project(TaskScheduler)

set(CMAKE_CXX_STANDARD 17)

add_executable(TaskScheduler src/main.cpp src/scheduler.cpp src/task.cpp)
