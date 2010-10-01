# the configured options and settings for Tutorial
cmake_minimum_required (VERSION 2.6)

add_library (MathFunctions mysqrt.cpp)

install (TARGETS MathFunctions DESTINATION bin)
install (FILES MathFunctions.h DESTINATION include)
