cmake_minimum_required(VERSION 3.0.2)

project(fanuc_m20ia_tools)

find_package(catkin REQUIRED COMPONENTS
  rviz
  xacro
)

catkin_package()

install(DIRECTORY meshes urdf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION})