cmake_minimum_required (VERSION 2.6)
project (scxvid)
add_executable(scxvid scxvid.c)
target_link_libraries (scxvid  "-lxvidcore")