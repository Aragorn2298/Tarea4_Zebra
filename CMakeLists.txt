cmake_minimum_required(VERSION 3.7)
project(Tarea4)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Evaluador.h Evaluador.cpp Mascota.cpp Mascota.h)
add_executable(Tarea4 ${SOURCE_FILES})