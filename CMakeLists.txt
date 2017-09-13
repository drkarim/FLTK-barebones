cmake_minimum_required(VERSION 2.8)
 
PROJECT(HelloWorldFLTK)

FIND_PACKAGE(FLTK REQUIRED)


 
add_executable(helloworldfltk HelloWorld.cxx)
 
TARGET_LINK_LIBRARIES(helloworldfltk ${FLTK_LIBRARIES})