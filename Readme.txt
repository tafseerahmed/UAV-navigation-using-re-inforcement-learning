README file
===========

Major Project 2018
By Abdul Mohsin Siddiqi, Zaiyan Alam, Tafseer Ahmed:

PREREQUISITES:

Requirements:
-Ubuntu 16.04 LTS
-Ros-kinetic
-Gazebo 7.0.0
-Gym 0.8.0 (NOT latest 0.10.5)

Changelog:
-Install missing pkgs as per the "pip pkgs" of "constructsim online ros terminal" 
-Gazebo models from Bitbucket   in ~/.gazebo/models/
-Created Folder gazebo_model in /usr/share and transferred above models
-ConstructSim Simulators (parrot_drone + others) from Bitbucket (+clone from constuctsim ros the following: bin and plugins in sjtu_drone folder)
-Add Ignition missing header files (/usr/share/ignition/math/   (10 files))
-Copied media and world from /usr/share/gazebo7 to /usr/share/gazebo
-Externally cmake action_controller before catkin_make all pkgs
-Changed version of gazebo in script files of parrot_ardrone/sjtu_drone
-Include xml version in ardrone_igniteworld.world of parrot_drone/drone_construct

---------------------------------------------------------------------------------------------------------------------------------------------

PART-1 of this module contains modules, packages, results and videos pertaining to Reinforcement Learning Part of our Project:
- Done Specifications
- Training Module
- Simulation
- Screenshots
- Results
- Graph Plots
- Video Demonstration for RL part

PART-2 of this module contains modules, packages, results and videos pertaining to Computer Vision Part of our Project:
- PTAM modules and specifications
- Video Demonstration for CV part
