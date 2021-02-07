# amr

Simulation of the robot in an empty world:
```
roslaunch amr_description amr_empty_world.launch
```

Simulation of the robot in the warehouse:
```
roslaunch amr_description amr_warehouse.launch
```

Navigation for the robot:
```
roslaunch amr_navigation amr_navigation.launch
```

Go to a fixed position:
```
rosrun amr_navigation go_location.py
```
