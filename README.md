# YouBot Velodyne Integration
Added a configuration of youbot with VLP-16 on top of the manipulator

### Installation
	cd ~/catkin_ws/src
    git clone http://github.com/youbot/youbot_description.git -b kinetic-devel
    git clone https://github.com/youbot/youbot_simulation.git
    git clone https://github.com/florianshkurti/velodyne_simulator.git
    git clone https://github.com/team-vigir/flexbe_behavior_engine.git

### Further recommended repos

* [youbot_behaviors](https://github.com/FlexBE/youbot_behaviors)

### Usage

    source ~/catkin_ws/devel/setup.bash
    roslaunch youbot_launch youbot_velodyne.launch
