cmake_minimum_required(VERSION 3.10)
project(solver)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Подключаем библиотеки


# Создаем исполняемый файл
add_executable(solver equation.cpp)

# Линкуем библиотеки
target_link_libraries(solver formatter_ex solver_lib)

