simple_test_atlas_moveit
========================

Repository dedicated to testing and debugging basic planning issues with atlas

```
mkdir atlas_test/src
cd atlas_test/src
wstool init .
wstool merge https://raw.githubusercontent.com/skohlbr/simple_test_atlas_moveit/master/simple_test_atlas_moveit.rosinstall
```

source ROS version you´d like, for instance

```
source /opt/ros/groovy/setup.bash
```

Build
```
cd ..
catkin_make
```

Source setup.bash:
```
source devel/setup.bash
```