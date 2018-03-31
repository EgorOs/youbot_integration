# YouBot Velodyne Integration
Added a configuration of youbot with VLP-16 on top of the manipulator

### Additionally required repos

* [flexbe_behavior_engine](https://github.com/team-vigir/flexbe_behavior_engine)
* [velodyne_simulator](https://github.com/florianshkurti/velodyne_simulator)

Make sure that you installed description and simulation from this repos

* [youbot_simulation](https://github.com/youbot/youbot_simulation)
* [youbot_description](https://github.com/youbot/youbot_description)

### Further recommended repos

* [youbot_behaviors](https://github.com/FlexBE/youbot_behaviors)

### Usage

    source ~/catkin_ws/devel/setup.bash
    roslaunch youbot_launch youbot_velodyne.launch
