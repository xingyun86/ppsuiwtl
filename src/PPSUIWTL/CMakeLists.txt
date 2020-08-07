# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

set(project_name PPSUIWTL)
project (${project_name})

# Include sub-projects.
add_subdirectory("DockTabs")
