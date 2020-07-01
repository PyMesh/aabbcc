cmake_minimum_required(VERSION 3.11.0)

project(aabbcc)

add_library(aabbcc src/aabb.h src/aabb.cc)
install(TARGETS aabbcc ARCHIVE DESTINATION lib)
install(FILES src/aabb.h DESTINATION include/aabbcc/)
