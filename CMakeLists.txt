cmake_minimum_required(VERSION 3.15)
project(liburing_examples C)

set(CMAKE_C_STANDARD 99)

add_executable(client client.c)
target_link_libraries(client uring)

add_executable(server server.c)
target_link_libraries(server uring)

