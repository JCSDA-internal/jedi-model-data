# (C) Copyright 2025- UCAR.
#
# This software is licensed under the terms of the Apache Licence Version 2.0
# which can be obtained at http://www.apache.org/licenses/LICENSE-2.0.

cmake_minimum_required(VERSION 3.12)
project(
  jedi-model-data
  VERSION 1.0.0
  DESCRIPTION "Test Files for JEDI Repos that define classes for Model Space (e.g., Vader, Saber)"
)

find_package(ecbuild QUIET)
include(ecbuild_system NO_POLICY_SCOPE)
ecbuild_declare_project()
set(CMAKE_DIRECTORY_LABELS ${PROJECT_NAME})
ecbuild_install_project(NAME ${PROJECT_NAME})
ecbuild_print_summary()
