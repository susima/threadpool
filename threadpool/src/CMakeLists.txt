PROJECT(threadpool_with_test)
SET(SRC threadpool.cpp )
SET(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11 -g -Wall -Wno-unused-variable -pthread")
ADD_EXECUTABLE( ${PROJECT_NAME} ${SRC} )
