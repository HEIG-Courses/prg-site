# Modèle de CMakeLists.txt pour un projet PRG
cmake_minimum_required(VERSION 3.28)
project(mon_projet CXX)                 # nom du projet, à adapter

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_compile_options(-Wall -Wextra -Wpedantic -Wconversion)

# Un fichier source par ligne ; CLion propose de les ajouter ici.
add_executable(${PROJECT_NAME}
        main.cpp
)
