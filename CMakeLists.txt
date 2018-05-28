cmake_minimum_required(VERSION 2.6)
project(testgtest)

add_executable(testgtest main.cpp)

target_link_libraries(testgtest gtest gtest_main pthread)

install(TARGETS testgtest RUNTIME DESTINATION bin)
