cmake_minimum_required(VERSION 3.16)

project(Demo VERSION 0.0.1 LANGUAGES C CXX)

find_package(Python COMPONENTS Interpreter Development)	# find Python interpreter and library
set(Python_FIND_REGISTRY "LAST")
message(STATUS "Python_EXECUTABLE = ${Python3_EXECUTABLE}")
message(STATUS "Python_STDLIB     = ${Python3_STDLIB}")
message(STATUS "Python_STDARCH    = ${Python3_STDARCH}")
message(STATUS "Python_SITELIB    = ${Python3_SITELIB}")
message(STATUS "Python_INCLUDE_DIRS = ${Python3_INCLUDE_DIRS}")
message(STATUS "Python_LIBRARY_DIRS = ${Python3_LIBRARY_DIRS}")
message(STATUS "Python_RUNTIME_LIBRARY_DIRS = ${Python3_RUNTIME_LIBRARY_DIRS}")
