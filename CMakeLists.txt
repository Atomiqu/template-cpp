cmake_minimum_required(VERSION 3.17 FATAL_ERROR)

project("--name--"
        VERSION 0.0.1
        HOMEPAGE_URL "--repo--"
        LANGUAGES C CXX
        )

set(CMAKE_OBJECT_PATH_MAX 512)

if(WIN32)
    set(CMAKE_WINDOWS_EXPORT_ALL_SYMBOLS ON)
endif()

add_subdirectory(dependencies)
#add_subdirectory(src)
#add_subdirectory(samples)
