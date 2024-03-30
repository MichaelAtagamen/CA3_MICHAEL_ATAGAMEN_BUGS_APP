cmake_minimum_required(VERSION 3.21)
project(CA3_MICHAEL_ATAGAMEN_BUGS_APP)

set(CMAKE_CXX_STANDARD 11)

add_executable(CA3_MICHAEL_ATAGAMEN_BUGS_APP main.cpp)

set(SFML_STATIC_LIBRARIES TRUE)
set(SFML_DIR C:/SFML/SFML-2.6.1/lib/cmake/SFML)
find_package(SFML COMPONENTS system window graphics audio network REQUIRED)

include_directories(C:/SFML/SFML-2.6.1/include)
target_link_libraries(CA3_MICHAEL_ATAGAMEN_BUGS_APP sfml-system sfml-window sfml-graphics sfml-audio)
