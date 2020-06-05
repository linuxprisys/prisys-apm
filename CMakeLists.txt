cmake_minimum_required(VERSION 3.13)
project(prisys-adm)

aux_source_directory(src SOURCES)

add_executable(${PROJECT_NAME} ${SOURCES})
target_link_libraries(libxml2)