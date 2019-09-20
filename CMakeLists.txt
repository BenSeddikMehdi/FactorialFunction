cmake_minimum_required(VERSION 3.14)
project(factNum_pkg C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(factNum_pkg
        factNum.c
        factNum.h
        factNum_initialize.c
        factNum_initialize.h
        factNum_terminate.c
        factNum_terminate.h
        factNum_types.h
        main.c
        main.h
        rt_nonfinite.c
        rt_nonfinite.h
        rtGetInf.c
        rtGetInf.h
        rtGetNaN.c
        rtGetNaN.h
        rtwtypes.h
        tmwtypes.h)
