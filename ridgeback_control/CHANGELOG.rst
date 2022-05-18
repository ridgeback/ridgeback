^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ridgeback_control
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.3.2 (2022-05-17)
------------------
* Enable subst_value when loading config_extras (`#48 <https://github.com/ridgeback/ridgeback/issues/48>`_)
* Add twist_mux
* Bump CMake version to avoid CMP0048 warning.
* Contributors: Chris I-B, Joey Yang, Tony Baltovski

0.3.1 (2022-01-12)
------------------
* add predict_to_current_time param
* Add envar to set joy device (`#44 <https://github.com/ridgeback/ridgeback/issues/44>`_)
  * Add the RIDGEBACK_JOY_DEVICE envar, move the control_extras to the end of control.launch so it can be used to override anything
  * Don't use the envar for the joy device when the PS3 flag is enabled
  * Add the default device for the ps3 configuration
  * Remove the joy device from the ps4 config; we explicitly set it with the envar
* Contributors: Chris I-B, Ebrahim

0.3.0 (2020-05-19)
------------------
* Fix the default device for the PS4 controller to match with the updated udev rules for bionic
* Contributors: Chris I-B

0.2.3 (2020-03-04)
------------------
* Fix controller odom bug, it works well in multi robots case now
* Contributors: yizheng

0.2.2 (2019-03-25)
------------------
* Changed boost::shared_ptr to urdfdom shared pointers
* ridgeback_control: fixed missing calculation of wheels_k\_ (regression from daa4bc9050f786ed092fab911dd217da6febeae0)
* Simplify boolean logic for wheel separation checks
* Allow URDF to be optional
* Contributors: Catherine Wong, Chad Rockey, Johannes Meyer, Tony Baltovski

0.2.1 (2018-04-12)
------------------
* Added support for planar motion using interactive markers.
* [ridgeback_control] Made PS4 default controller.
* Contributors: Tony Baltovski

0.2.0 (2018-04-12)
------------------
* Removed tight default rolling window
* Updated rolling window for odom responsiveness.  Minor changes to control and urdf syntax for kinetic
* Updated to Package format 2.
* [ridgeback_control] Added ability to override default control parameters with environment variables.
* Contributors: Dave Niewinski, Tony Baltovski

0.1.10 (2017-06-26)
-------------------

0.1.9 (2017-04-17)
------------------
* Updated maintainer.
* Contributors: Tony Baltovski

0.1.8 (2016-09-30)
------------------

0.1.7 (2016-07-18)
------------------
* Fixed teleop angular axis for PS4.
* Contributors: Tony Baltovski

0.1.6 (2016-05-25)
------------------
* Added support for PS4 controller.
* Contributors: Tony Baltovski

0.1.5 (2016-04-22)
------------------

0.1.4 (2016-04-18)
------------------

0.1.3 (2016-03-02)
------------------
* Updated URDF for physical changes.
* Updated control limits.
* Removed yaw estimate from robot_localization.
* Contributors: Tony Baltovski

0.1.2 (2015-12-22)
------------------
* Added wheel separation override.
* Contributors: Tony Baltovski

0.1.1 (2015-12-01)
------------------

0.1.0 (2015-11-19)
------------------
* Initial ridgeback release.
* Contributors: Mike Purvis, Tony Baltovski
