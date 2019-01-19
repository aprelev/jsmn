cmake_minimum_required (VERSION 3.2)

project (jsmn)

add_library(jsmn jsmn.c)
target_include_directories(jsmn PUBLIC include)
