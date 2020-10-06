cmake_minimum_required(VERSION 3.16)

project(SugarPP)

add_library(SugarPP INTERFACE)

set(SugarPPIncludeDir
    When/
    IO/
    Range/
    Traits/
)

target_include_directories(SugarPP INTERFACE
    ${SugarPPIncludeDir}
)

message(${SugarPPIncludeDir})