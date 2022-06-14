cmake_minimum_required(VERSION 3.12)

project("dphwtd")

file(GLOB MODS "src/*.ixx")
add_executable(dphwtd "src/main.cpp" ${MODS})

set_property(TARGET dphwtd PROPERTY CXX_STANDARD 20)
