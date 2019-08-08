cmake_minimum_required(VERSION 3.14)
project(libsvm)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(svm-train
        svm-train.c
        svm.cpp
        svm.h)

add_executable(svm-predict
        svm-predict.c
        svm.cpp
        svm.h)
