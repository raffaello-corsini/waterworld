# Preferable to avoid warnings during execution
cmake_minimum_required (VERSION 2.8.12)

# Set the executable along with the required source files
add_executable(project project.cc)

# Instruct to link against the ariadne library, and the bdd library
target_link_libraries(project ariadne bdd)
