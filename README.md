# virat_navigation
package for SLAM and navigation of Clueless Virat

Create a map
------------

Launch world
```bash
roslaunch virat_navigation virat_nav_world.launch
```

Start gmapping
```bash
roslaunch virat_navigation gmapping_demo.launch
```

Launch rviz
```bash
roslaunch virat_navigation virat_gmapping_rviz.launch
```

Launch teleop
```bash
roslaunch virat_teleop virat_teleop_key.launch
```

Save map
```bash
rosrun map_server map_saver -f ~/map_for_navigation
```
