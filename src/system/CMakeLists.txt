CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
PROJECT(TDengine)

ADD_SUBDIRECTORY(detail)

IF (TD_EDGE)
  ADD_SUBDIRECTORY(lite)
ENDIF ()