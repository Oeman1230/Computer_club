
cmake_minimum_required(VERSION 3.29)

set(PROJ_NAME ComputerClubTask)
set(EXEC_NAME task)

project(PROJ_NAME)

set(CUR_DIR_PATH ${CMAKE_CURRENT_SOURCE_DIR})


set(SOURCE_FILES    
                    ${CUR_DIR_PATH}/src/Main.cpp
                    ${CUR_DIR_PATH}/src/ComputerClub.cpp)


include_directories(${CUR_DIR_PATH}/src)


add_executable(${EXEC_NAME} ${SOURCE_FILES})

