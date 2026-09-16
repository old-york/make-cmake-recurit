cmake_minimum_required(VERSION 3.16)

project(calculator LANGUAGES C)

# TODO: create an executable target named calculator
# Hint: sources are in src/main.c and src/calculator.c

# TODO: add the include directory for the calculator target
add_executable(calculator
    src/main.c
    src/calculator.c)
target_include_directories(calculator
    PRIVATE
    ${CMAKE_CURRENT_SOURCE_DIR}/include
)
