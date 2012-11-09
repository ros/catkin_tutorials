# %Tag(FULLTEXT)%
cmake_minimum_required(VERSION 2.8.3)
project(beginner_tutorials)

# Load catkin and all dependencies required for this package
find_package(catkin REQUIRED COMPONENTS roscpp rospy std_msgs)

## System dependencies, Boost as an example, can be found like this
## usage examples below
# find_package(Boost REQUIRED COMPONENTS system)

## uncomment if the package has a setup.py
# catkin_python_setup()

## Declare ROS messages and services here

# add_message_files(
#   DIRECTORY msg
#   FILES
#     MyMessage1.msg
#     MyMessage2.msg
# )

# add_service_files(
#   DIRECTORY srv
#   FILES
#     MyService1.srv
#     MyService2.srv
# )

## Uncomment this if you have declared any messages or services
## and specify dependencies if any
# generate_messages(DEPENDENCIES std_msgs)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES ${PROJECT_NAME}
#  CATKIN_DEPENDS catkin-pkg1 catkin-pkg2
#  DEPENDS 3rd-party-package Boost
)

## Specify additional locations of header files
# include_directories(include ${catkin_INCLUDE_DIRS})

## Use this to declare libraries that this package creates
# add_library(${PROJECT_NAME}
#   src/${PROJECT_NAME}/library.cpp
# )

## Use this to declare executables that this package creates
# add_executable(${PROJECT_NAME}_node src/main.cpp)

## Use this to e.g. make your executables depend on your libraries
# add_dependencies(${PROJECT_NAME}_node ${PROJECT_NAME})

## specify what c++ libraries your c++ executable should be linked against
# target_link_libraries(${PROJECT_NAME}_node
#   ${catkin_LIBRARIES} ${Boost_LIBRARIES}
# )

## Use this to declare executable scripts (Python etc.)
# install(PROGRAMS
#   scripts/my_python_script
#   DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION})

## Use this to declare c++ executables and/or libraries
# install(TARGETS ${PROJECT_NAME}_node
#   ARCHIVE DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION}
#   LIBRARY DESTINATION ${CATKIN_PACKAGE_LIB_DESTINATION})

## If specific folders are to be installed (no executable or library), use this
# install(DIRECTORY include/${PROJECT_NAME}/
#   DESTINATION ${CATKIN_PACKAGE_INCLUDE_DESTINATION}
#   FILES_MATCHING PATTERN "*.h"
#   PATTERN ".svn" EXCLUDE)

## This is for any other files that should go into an install
# install(FILES
#   myfile1
#   myfile2
#   DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
# )

## Use this for c++ gtest unit tests
# catkin_add_gtest(${PROJECT_NAME}-test test/mytest)
# if(TARGET ${PROJECT_NAME}-test)
#   target_link_libraries(${PROJECT_NAME}-test ${PROJECT_NAME}_node)
# endif()

## Use this to declare python unit test folders
# catkin_add_nosetests(test)

# %EndTag(FULLTEXT)%