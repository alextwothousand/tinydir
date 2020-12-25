cmake_minimum_required(VERSION 3.17)
project(tinydir)

set (headers ${PROJECT_SOURCE_DIR}/tinydir.h)
add_library(tinydir STATIC ${headers})

target_include_directories(tinydir PUBLIC ${headers})