#1.定义cmake版本
cmake_minimum_required(VERSION 3.9.5)
#2.设置项目名称
project(libarchive)

add_subdirectory(readonlylibarchiveplugin)

add_subdirectory(readwritelibarchiveplugin)
