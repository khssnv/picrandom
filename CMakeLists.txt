cmake_minimum_required(VERSION 3.7)
project( imgrandom )
set (CMAKE_CXX_STANDARD 17)
find_package( OpenCV REQUIRED )
add_executable( imgrandom src/main.cpp )
target_link_libraries( imgrandom ${OpenCV_LIBS} stdc++fs )
