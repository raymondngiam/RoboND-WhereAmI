# RoboND-WhereAmI

---

### Demo

![alt text](images/demo.gif)

### Dependencies

- ROS Kinetic
- CMake 2.8


### Installing ROS dependencies

```bash
$ cd <repo root>/catkin_ws
$ sudo apt update
$ rosdep install --from-paths ./src --ignore-packages-from-source -y
```

### Compiling the Program

```bash
$ cd <repo root>/catkin_ws
$ catkin_make
```

### Launch the world from `my_robot` package

```bash
$ cd <repo root>/catkin_ws
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```

### Running `amcl` from `my_robot` package

```bash
$ cd <repo root>/catkin_ws
$ source devel/setup.bash
$ roslaunch my_robot amcl.launch
```