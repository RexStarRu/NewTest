cmake_minimum_required (VERSION 3.17 FATAL_ERROR)

set (PROJECT_NAME 
			NewTest
)

project(${PROJECT_NAME})

set(SOURCES 
		src/Main.cpp
)

add_executable(${PROJECT_NAME} ${SOURCES})

set_target_properties(${PROJECT_NAME} PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)

