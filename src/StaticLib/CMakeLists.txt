project(StaticLib)

add_library(${PROJECT_NAME} STATIC staticLib1.cpp staticLib2.cpp)
target_include_directories(${PROJECT_NAME} PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)
