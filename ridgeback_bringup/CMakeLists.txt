cmake_minimum_required(VERSION 2.8.3)
project(ridgeback_bringup)

find_package(catkin REQUIRED COMPONENTS roslaunch)

catkin_package()

roslaunch_add_file_check(launch/accessories.launch)

install(DIRECTORY launch
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(FILES scripts/can-udp-bridge.conf
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)

install(PROGRAMS scripts/install
  DESTINATION ${CATKIN_PACKAGE_BIN_DESTINATION}
)
