cmake_minimum_required(VERSION 3.16)
project(tictactoe)

set(CMAKE_CXX_STANDARD 17)

set(SOURCES src/tictactoe.cpp  src/ai.cpp src/board.cpp)

add_executable(${PROJECT_NAME} ${SOURCES})
