^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ridgeback_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.9 (2017-04-17)
------------------
* Fixed malformed stl meshes.
* Reduced gyroscopes noise.
* Reverted dimensions of chassis collision mesh to allow laser rays out.
* Added Sick S300 laser and Microstrain IMU upgrade accessories.
* Updated material properties for Ridgeback.
* Fixed IMU offset.
* Updated maintainer.
* Contributors: Tony Baltovski

0.1.8 (2016-09-30)
------------------
* Added environment variable to set the robot configuration and empty configuration.
* Added cmd_vel timeout for force based move plugin.
* Contributors: Tony Baltovski

0.1.7 (2016-07-18)
------------------
* Removed unused mesh.
* Uncommented RIDGEBACK_URDF_EXTRAS include.
* Contributors: Tony Baltovski

0.1.6 (2016-05-25)
------------------
* Added params for hector_gazebo_plugins/gazebo_ros_force_based_move.
* Using ros_force_based_move from ridgeback_simulator.
* Fixed xacro xmlns declaration and added Hokuyo minimun intensity.
* Contributors: Tony Baltovski

0.1.5 (2016-04-22)
------------------
* Added support for Hokuyo URG-10LX.
* Contributors: Tony Baltovski

0.1.4 (2016-04-18)
------------------
* Added lms1xx as run dependency.
* Contributors: Tony Baltovski

0.1.3 (2016-03-02)
------------------
* Updated URDF for physical changes.
* Simulation using gazebo_ros_force_based_move.
* Contributors: Mike Purvis, Tony Baltovski

0.1.2 (2015-12-22)
------------------

0.1.1 (2015-12-01)
------------------
* Added manufacturer to laser environment variables.
* Contributors: Tony Baltovski

0.1.0 (2015-11-19)
------------------
* Initial ridgeback description release.
* Contributors: Mike Purvis, Tony Baltovski
