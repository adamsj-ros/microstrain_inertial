^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package mscl_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.0.5 (2021-10-19)
------------------

2.0.4 (2021-09-08)
------------------
* Upgrade CMake version and removes unused include in examples
* Contributors: robbiefish

2.0.3 (2021-09-08)
------------------

2.0.2 (2021-08-30)
------------------
* Fixes cmake warnings and updates maintainers
* Contributors: robbiefish

2.0.1 (2021-08-24)
------------------
* Moves submodules to accomodate ROS build farm
* Contributors: Rob Fisher

2.0.0 (2021-08-24)
------------------
* Moves service messages to msgs package
* Contributors: Rob Fisher

1.1.4 (2021-07-30)
------------------
* Please see changelog
* Added aiding measurement summary for each GNSS (GQ7 only)
  Added MSCL version output when node starts
* Merge pull request `#54 <https://github.com/LORD-MicroStrain/ROS-MSCL/issues/54>`_ from civerachb-cpr/master
  Explicitly name the mscl_msgs package
* Explicitly name the mscl_msgs package instead of using the directory name; the dir name isn't reliable on some build-farms that extract each package into a separate working directory
* Contributors: Chris Iverach-Brereton, Nathan Miller, nathanmillerparker

1.1.3 (2021-04-21)
------------------
* Removed duplicate Filter LLH Pos entry in message format
  Preparing for release on Bloom
* - Driver modified to support MSCL version 61.1.6
  - Fixed missing boolean set for RTK status message publishing
* Merge pull request `#34 <https://github.com/LORD-MicroStrain/ROS-MSCL/issues/34>`_ from CaptKrasno/msg
  Moved Messages to Separate Package and renamed them to match ros convention
* Separated Messages into a second package and changed naming to match ros convention
* Contributors: Kristopher Krasnosky, Nathan Miller, nathanmillerparker

0.0.4 (2019-10-07)
------------------

0.0.3 (2019-08-05)
------------------

0.0.2 (2019-05-28)
------------------
