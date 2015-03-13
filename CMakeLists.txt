cmake_minimum_required(VERSION 2.8.3)
project(pr2_joint_limit_check)

## Find catkin macros and libraries
## if COMPONENTS list like find_package(catkin REQUIRED COMPONENTS xyz)
## is used, also find other catkin packages
find_package(catkin REQUIRED COMPONENTS)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES test
CATKIN_DEPENDS rospy
#  DEPENDS system_lib
)


install(PROGRAMS scripts/pr2_joint_limit_check
)
