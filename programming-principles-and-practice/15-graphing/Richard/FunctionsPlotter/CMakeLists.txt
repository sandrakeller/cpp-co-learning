CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
PROJECT(FunctionsPloter)

ADD_DEFINITIONS("-std=c++11")

FIND_PACKAGE(FLTK REQUIRED)

ADD_EXECUTABLE (FunctionsPloter
    main.cpp
    Window.cpp
    Simple_window.cpp
    GUI.cpp
    Graph.cpp
)

TARGET_LINK_LIBRARIES(FunctionsPloter
    ${FLTK_LIBRARIES}
)
