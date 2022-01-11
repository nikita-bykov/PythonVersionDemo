cmake_minimum_required(VERSION 3.16)

project(Demo VERSION 0.0.1 LANGUAGES C CXX)

set(Python3_FIND_REGISTRY "LAST")

find_package(Python3 COMPONENTS Interpreter Development)	# find Python interpreter and library
find_package(Python COMPONENTS Interpreter Development)

message(STATUS "Python3_EXECUTABLE = ${Python3_EXECUTABLE}")
message(STATUS "Python3_STDLIB     = ${Python3_STDLIB}")
message(STATUS "Python3_STDARCH    = ${Python3_STDARCH}")
message(STATUS "Python3_SITELIB    = ${Python3_SITELIB}")
message(STATUS "Python3_INCLUDE_DIRS = ${Python3_INCLUDE_DIRS}")
message(STATUS "Python3_LIBRARY_DIRS = ${Python3_LIBRARY_DIRS}")
message(STATUS "Python3_RUNTIME_LIBRARY_DIRS = ${Python3_RUNTIME_LIBRARY_DIRS}")
