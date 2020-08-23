PROJECT( eyelike_project )
#FIND_PACKAGE( OpenCV REQUIRED )
cmake_minimum_required(VERSION 2.8)
#set(OpenCV_DIR /home/cly/developsoft/hisilicon/otherware/share/OpenCV)
find_package( OpenCV REQUIRED )

SET(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${PROJECT_BINARY_DIR}/bin)
set(CMAKE_BINARY_DIR ${PROJECT_BINARY_DIR}/bin)
set(CMAKE_CXX_STANDARD 11)

add_subdirectory(src)
