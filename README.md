# YouBot Velodyne Integration
Added a configuration of youbot with VLP-16 on top of the manipulator

### Installation
	cd ~/catkin_ws/src
    git clone http://github.com/youbot/youbot_description.git -b kinetic-devel
    git clone https://github.com/youbot/youbot_simulation.git
    git clone https://bitbucket.org/DataspeedInc/velodyne_simulator.git
    git clone https://github.com/team-vigir/flexbe_behavior_engine.git
    cd ~/catkin_ws
    catkin_make

### Known issues

* Reinstall gazebo
    sudo apt-get install ros-kinetic-gazebo-ros-pkgs ros-kinetic-gazebo-ros-control
* Install joint state contoroller
    sudo apt-get install ros-kinetic-joint-state-controller

### Further recommended repos

* [youbot_behaviors](https://github.com/FlexBE/youbot_behaviors)

### Usage

    source ~/catkin_ws/devel/setup.bash
    roslaunch youbot_launch youbot_velodyne.launch
