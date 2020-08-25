# Titan_Gokarts

Welcome to the [Cosin lab](https://inc.kmutt.ac.th/~yoodyui/Clips/index.html) RoboRacing software repository! This document will give you a brief outline of the repository's layout and some simple instructions for setting up the project. For more detailed information, please visit the [wiki](https://inc.kmutt.ac.th/~yoodyui/Clips/index.html).

[![Software Lead](https://img.shields.io/badge/Software%20Lead-Punyapat%20Areerob-blue.svg)](https://github.com/59070501436)

[![Project Manager](https://img.shields.io/badge/Project%20Manager-Punyapat%20Areerob-blue.svg)](https://github.com/59070501436)

[![Maintainer](https://img.shields.io/badge/Maintainer-Punyapat%20Areerob-blue.svg)](https://github.com/59070501436)


## Organization
This repository is comprised of multiple ROS packages and one sandbox folder for miscellaneous resources.

**Tai_commone**: This package contains mission code for the [test](https:google.com).

The following files and folders enable our continuous integration system.

* Dockerfile

## Installation

This repository should be cloned into the src directory of a catkin workspace. Use ```catkin_make``` in the workspace directory to build the code. (NOTE: Be sure to ```source devel/setup.sh``` before referencing roboracing packages.)

For a guide on installing our code please go to [our guide](https://wiki.robojackets.org/RoboRacing_Software_Installation_Instructions).

## Simulation

You can get started with the RoboRacing code base right away by launching our simulator!

The following command will load our platform in the testrun track:
```
roslaunch gg
```