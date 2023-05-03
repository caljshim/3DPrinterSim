cmake_minimum_required(VERSION 3.12)
project(Firmware LANGUAGES CSharp)
set(CMAKE_DOTNET_TARGET_FRAMEWORK_VERSION "4.5.2")
set(CMAKE_CSharp_FLAGS "/langversion:7")

add_subdirectory(Tests)

include(CTest)
