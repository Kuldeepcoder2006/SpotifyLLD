cmake_minimum_required(VERSION 3.10)
project(SpotifyLLD CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(music_player MusicPlayerApp/main.cpp)
target_include_directories(music_player PRIVATE MusicPlayerApp)
