# YouBot Velodyne Integration
Added a configuration of youbot with VLP-16 on top of the manipulator

### Additionally required repos

* [youbot_description](https://github.com/mas-group/youbot_description)
* [flexbe_behavior_engine](https://github.com/team-vigir/flexbe_behavior_engine)
* [velodyne_simulator](https://github.com/florianshkurti/velodyne_simulator)

Make sure that you installed youbot_simulation from this repo

* [youbot_simulation](https://github.com/youbot/youbot_simulation)

### Further recommended repos

* [youbot_behaviors](https://github.com/FlexBE/youbot_behaviors)

### Usage

    source ~/catkin_ws/devel/setup.bash
    roslaunch youbot_launch youbot_velodyne.launch
