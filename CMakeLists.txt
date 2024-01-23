cmake_minimum_required(VERSION 3.0)
project(SampleJavaCmake)

find_package(Java REQUIRED)

include(UseJava)


add_jar(SampleJavaCmake src/Main.java ENTRY_POINT Main)
