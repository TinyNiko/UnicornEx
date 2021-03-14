cmake_minimum_required(VERSION 3.2)

PROJECT(unicornex)

INCLUDE_DIRECTORIES(
include
)

AUX_SOURCE_DIRECTORY(src DIR_SRCS)


SET(unicornex
${DIR_SRCS}
)


ADD_EXECUTABLE(${PROJECT_NAME} ${dy_vmp})
