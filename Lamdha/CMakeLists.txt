cmake_minimum_required(VERSION 3.0)

project(lamdha
    VERSION 0.1
    LANGUAGES CXX
    DESCRIPTION "A sample app to showcase the usage of the time core"
)


add_executable(${PROJECT_NAME} ./src/main.cpp)

target_link_libraries(${PROJECT_NAME} PRIVATE curl)
