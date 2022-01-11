cmake_minimum_required(VERSION 3.16)

project(Demo VERSION 0.0.1 LANGUAGES C CXX)

set(Python_FIND_REGISTRY "LAST")
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

message(STATUS "Python_EXECUTABLE = ${Python_EXECUTABLE}")
message(STATUS "Python_STDLIB     = ${Python_STDLIB}")
message(STATUS "Python_STDARCH    = ${Python_STDARCH}")
message(STATUS "Python_SITELIB    = ${Python_SITELIB}")
message(STATUS "Python_INCLUDE_DIRS = ${Python_INCLUDE_DIRS}")
message(STATUS "Python_LIBRARY_DIRS = ${Python_LIBRARY_DIRS}")
message(STATUS "Python_RUNTIME_LIBRARY_DIRS = ${Python_RUNTIME_LIBRARY_DIRS}")
