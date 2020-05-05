# Project: Build My World
In this project, a Gazebo World environment is designed by including multiple models.  

The simulation world folder has the following directory structure:

    .Project1                          # Build My World Project 
    ├── model                          # Model files 
    │   ├── mybuilding
    │   │   ├── model.config
    │   │   ├── model.sdf
    │   ├── robot_model
    │   │   ├── model.config
    │   │   ├── model.sdf
    ├── script                         # Gazebo World plugin C++ script      
    │   ├── hello.cpp
    ├── world                          # Gazebo main World containing models 
    │   ├── myworld_2robots.world
    ├── CMakeLists.txt                 # Link libraries 
    └──                              
