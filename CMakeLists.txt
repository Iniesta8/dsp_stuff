cmake_minimum_required(VERSION 3.6)
project(dsp_stuff)

set(CMAKE_C_STANDARD 90)

set(SOURCE_FILES main.c kiss_fftr.c kiss_fft.c kissfft.hh kiss_fftr.h kiss_fft.h _kiss_fft_guts.h)
add_executable(dsp_stuff ${SOURCE_FILES})