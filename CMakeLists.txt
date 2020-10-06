cmake_minimum_required(VERSION 3.16)

project(SugarPP)

add_library(SugarPP INTERFACE)
target_include_directories(SugarPP INTERFACE
    When/
    IO/
    Range/
    Traits/
)