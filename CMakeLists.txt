cmake_minimum_required(VERSION 3.20)
project(SDS)

add_definitions(-DSDS_TEST_MAIN)

add_executable(
    sds-test
        sds.c
)
