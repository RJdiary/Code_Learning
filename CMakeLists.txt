cmake_minimum_required(VERSION 4.0)
project(C_CRMDJT C)

set(CMAKE_C_STANDARD 11)

add_executable(
        C_CRMDJT C/CRMDJT/chapter_one.c
        C/CRMDJT/chapter_two.c
        C/CRMDJT/chapter_three.c
)
