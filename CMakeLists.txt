cmake_minimum_required(VERSION 3.19.8)
set(WORKSPACE_DIR ${CMAKE_SOURCE_DIR}/../.. CACHE PATH "root of the PID workspace directory")
list(APPEND CMAKE_MODULE_PATH ${WORKSPACE_DIR}/cmake) # using generic scripts/modules of the workspace
include(Package_Definition NO_POLICY_SCOPE)

project(my_first_PID_package)

PID_Package(
    AUTHOR             Fabian_Lopez
    YEAR               2023
    LICENSE            CeCILL
    DESCRIPTION        TODO: input a short description of package my_first_PID_package utility here
    VERSION            0.0.0
)

# All the functions commented below are optional and documented here https://pid.lirmm.net/pid-framework/assets/apidoc/html/pages/Package_API.html
# Ellipses (...) suggest you to read the documentation to find the appropriate syntax
#
# You can declare additional authors with:
# PID_Author(AUTHOR John Doe ...)
#
# Add necessary checks on your build environment (e.g needed tool, compiler version, etc) using:
# check_PID_Environment(...)
#
# Specify contraints on the target environment (e.g system configuration, OS, CPU architecture, etc) with:
# check_PID_Platform(...)
#
# Declare your package dependencies using:
# PID_Dependency(package-name ...)
#
# Publish your documentation, and optionally binaries, online with:
# PID_Publishing(...)

build_PID_Package()
