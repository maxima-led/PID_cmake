cmake_minimum_required(VERSION 3.20)

project(PID)

add_library(${PROJECT_NAME} STATIC
  PID.c
)

target_include_directories(${PROJECT_NAME} PUBLIC
  .
)
