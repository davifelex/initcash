cmake_minimum_required(VERSION 3.10)
project(initcash)

# Add cpp sources in project
file(GLOB SOURCES "sources/*.cpp")

# Create exe using cpp sources
add_executable(main ${SOURCES})