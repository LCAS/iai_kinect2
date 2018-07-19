^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package kinect2_viewer
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* libfreenect2 compiles as an external project from kinect2_bridge
* removed obsolete isnan and check the integer depth value instead of the float.
* CMake build fixes for OS X for CL.h based on equivalent fixes in libfreenect2
* Improved FAQ and fixed some spelling mistakes.
* updated README
* Prepared compatibility to OpenCV 3.
  Still only works with OpenCV 2.4.8 because cv_bridge needs it in Indigo/Jade.
* Switched to ros_console for output.
  Added colored output.
* improved READMEs.
* To fit catkin_make
* renamed depth_registration package to kinect2_registration.
  renamed registration_viewer package to kinect2_viewer.
* Contributors: Andrew Hundt, Kenta Yonekura, Thiemo Wiedemeyer, mfernandezcarmona@lincoln.ac.uk
