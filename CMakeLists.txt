cmake_minimum_required(VERSION 3.19)
project(nested_loopJoinClock_sweep C)

set(CMAKE_C_STANDARD 99)

add_executable(
        nested_loopJoinClock_sweep
        bnl.c
        bufpool.c
        bufpool.h
        )