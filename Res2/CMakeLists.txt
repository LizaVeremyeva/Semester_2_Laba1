cmake_minimum_required(VERSION 3.8)
set(PROJECT_NAME example) #задание значения переменной
project("${PROJECT_NAME}") #устанавливаем имя проекта
set(CMAKE_CXX_STANDARD 14) #устанавливаем 14 стандарт языка (набор поддерживаемых библиотек\команд)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)
add_executable("${PROJECT_NAME}" Laba2.cpp)
