cmake_minimum_required(VERSION 3.2)
project(Example C CXX)

# --> Creates an executable (target) from one or a set of source files
add_executable(target main.cpp)

# --> Set any property
# set_property(entitySpecific
#     [APPEND] [APPEND_STRING]
#     PROPERTY propName [value1 [value2 [...]]])

# --> Compiler Flags: set include directories for target
# set_property(target APPEND PROPERTY INCLUDE_DIRECTORIES /home/gabe/repos/learning/learning-cmake/libs/_example/source/include)