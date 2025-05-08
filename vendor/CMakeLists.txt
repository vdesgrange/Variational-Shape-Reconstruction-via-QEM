cmake_minimum_required(VERSION 3.31)

set(CMAKE_INCLUDE_CURRENT_DIR ON)

set(CGAL_Qt5_FOUND FALSE)
set(CGAL_DIR /Users/vdesgrange/Development/C_projects/TinyScannerResearch/Variational-Shape-Reconstruction-via-QEM/vendor/CGAL-5.5.5)
set(CGAL_SOURCE_DIR /Users/vdesgrange/Development/C_projects/TinyScannerResearch/Variational-Shape-Reconstruction-via-QEM/vendor/CGAL-5.5.5)
set(CGAL_BINARY_DIR /Users/vdesgrange/Development/C_projects/TinyScannerResearch/Variational-Shape-Reconstruction-via-QEM/vendor/CGAL-5.5.5)
set(Eigen_SOURCE_DIR /Users/vdesgrange/Development/C_projects/TinyScannerResearch/Variational-Shape-Reconstruction-via-QEM/vendor/eigen-3.4.0)
set(Eigen_BINARY_DIR /Users/vdesgrange/Development/C_projects/TinyScannerResearch/Variational-Shape-Reconstruction-via-QEM/vendor/eigen-3.4.0)

add_subdirectory(CGAL-5.5.5)
add_subdirectory(eigen-3.4.0)
add_subdirectory(scip-9.2.2)

