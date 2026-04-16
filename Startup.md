### Terminal 1 — Launch the perception pipeline:
```
cd <replace by proj location>
pixi shell 
cd ros2_ws 
source install/setup.bash 
ros2 launch s1s2_r1_perception perception.launch.py 
```

### Terminal 2 — Play the bag:
```
cd <replace by proj location>
pixi shell
source ros2_ws/install/setup.bash
ros2 bag play <replace by rosbag location> --clock
```
