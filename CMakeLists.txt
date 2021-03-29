cmake_minimum_required(VERSION 3.5)
project(ur_e_description)

find_package(ament_cmake REQUIRED)

include_directories(
)

install(
  DIRECTORY urdf meshes
  DESTINATION share/${PROJECT_NAME}
 )

 ament_package()