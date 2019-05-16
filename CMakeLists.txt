cmake_minimum_required(VERSION 3.13)
project(cradick_6 C)

set(CMAKE_C_STANDARD 99)

add_executable(cradick_6 userProcess oss.c userProcess.c VClock.c ClockSemaphore.c)