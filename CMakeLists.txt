cmake_minimum_required(VERSION 3.9)

project(FalloutSBX VERSION 0.1
    DESCRIPTION "A multiplayer sandbox mod for Fallout4"
    LANGUAGES CXX)

add_subdirectory(client)
add_subdirectory(server)