cmake_minimum_required(VERSION 3.18.4)
project(K22:Process_Communication)


#Bring the headers into the project
include_directories(Include)
 
#Add the sources:
file(GLOB SOURCES "src/*.cpp")
 
add_executable(Com_P2 ${SOURCES})  
