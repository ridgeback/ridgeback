^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ridgeback_navigation
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.3.2 (2022-05-17)
------------------
* Bump CMake version to avoid CMP0048 warning.
* Contributors: Tony Baltovski

0.3.1 (2022-01-12)
------------------
* Expose the scan_topic argument in the amcl and gmapping demos (`#43 <https://github.com/ridgeback/ridgeback/issues/43>`_)
* [Nav][AMCL] adds args to pass initial pose to AMCL
  This adds the ros launch arguments initial_pose_x, initial_pose_y and
  initial_pose_a which are passed through to the AMCL params of the same
  name.
  These args are defaulted to 0.0, 0.0, 0.0 as they were before so they
  should have no changing effects if not set.
  These args can be used to pre-seed the initial localization estimate.
  Which is useful when you know where in the map you've spawned the robot.
* Contributors: Alex Moriarty, Chris I-B

0.3.0 (2020-05-19)
------------------

0.2.3 (2020-03-04)
------------------

0.2.2 (2019-03-25)
------------------

0.2.1 (2018-04-12)
------------------

0.2.0 (2018-04-12)
------------------
* Updated to Package format 2.
* Contributors: Tony Baltovski

0.1.10 (2017-06-26)
-------------------

0.1.9 (2017-04-17)
------------------
* Changed amcl odom model type to omni-corrected.
* Updated maintainer.
* Contributors: Tony Baltovski

0.1.8 (2016-09-30)
------------------

0.1.7 (2016-07-18)
------------------

0.1.6 (2016-05-25)
------------------
* Updated laser scan topic and robot footprint.  Also, enabled holonomic motion.
* Contributors: Tony Baltovski

0.1.5 (2016-04-22)
------------------

0.1.4 (2016-04-18)
------------------

0.1.3 (2016-03-02)
------------------
* Removed CATKIN_IGNORE from ridgeback_navigation.
* ridgeback_navigation: remove deprecated footprint layer
* Simulation using gazebo_ros_force_based_move.
* Contributors: Achim Krauch, Mike Purvis, Tony Baltovski

0.1.2 (2015-12-22)
------------------

0.1.1 (2015-12-01)
------------------

0.1.0 (2015-11-19)
------------------
* Initial ridgeback release.
* Contributors: Mike Purvis, Tony Baltovski
