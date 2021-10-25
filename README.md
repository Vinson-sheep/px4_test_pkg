# Tutorials
**px4_test_pkg** is a simple tool for px4 uav testing. Before getting start, **mavros**、**mavros-extras**、**vrpn-ros-client** should be downloaded and well configurated.

## edit ~/.bashrc

```
// remote PC
export ROS_MASTER_URI=http://192.168.1.27:11311
export ROS_HOSTNAME=192.168.1.27

// uav
export ROS_MASTER_URI=http://192.168.1.27:11311
export ROS_HOSTNAME=192.168.1.41
```

## Run

```
// remote PC
roslaunch px4_test_pkg setup_act_ground.launch

// uav
roslaunch px4_test_pkg setup_act_onboard.launch
```

