cmake_minimum_required(VERSION 3.15)
project(rapidJSONExample)

set(CMAKE_CXX_STANDARD 17)

file(COPY sample_data/ DESTINATION sample_data/)

add_executable(rapidJSONExample main.cpp)
target_include_directories(rapidJSONExample PRIVATE rapidjson/)