cmake_minimum_required(VERSION 3.16)

project(Demo VERSION 0.0.1 LANGUAGES C CXX)
set(Python_FIND_REGISTRY "LAST")
find_package(Python COMPONENTS Interpreter Development)	# find Python interpreter and library

