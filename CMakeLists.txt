cmake_minimum_required(VERSION 3.12)

project("dphwtd")

file(GLOB SRCS "src/*.cpp")
add_executable(dphwtd ${SRCS})

set_property(TARGET dphwtd PROPERTY CXX_STANDARD 20)
