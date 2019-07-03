cmake_minimum_required( VERSION 2.8.3 )
project( syrena_gazebo_ar_track )

find_package( catkin REQUIRED COMPONENTS 
    roscpp
)

catkin_package(
    LIBRARIES ${PROJECT_NAME}
    DEPENDS roscpp
)

include_directories( ${catkin_INCLUDE_DIRS} )
