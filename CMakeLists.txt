cmake_minimum_required(VERSION 3.1...3.13)

if(${CMAKE_VERSION} VERSION_LESS 3.12)
    cmake_policy(VERSION ${CMAKE_MAJOR_VERSION}.${CMAKE_MINOR_VERSION})
endif()

project(ill_template VERSION 1.0
                  DESCRIPTION "ILL Template Project"
                  LANGUAGES CXX C)

add_subdirectory(src)
enable_testing()
add_subdirectory(tests)
add_subdirectory(apps)