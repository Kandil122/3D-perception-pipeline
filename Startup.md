### Terminal 1 — Launch the perception pipeline:
```
bashcd /media/adham/SSD1/rse-3d-perception-pipeline 
pixi shell 
cd ros2_ws 
source install/setup.bash 
ros2 launch s1s2_r1_perception perception.launch.py 
```

### Terminal 2 — Play the bag:
```
bashcd /media/adham/SSD1/rse-3d-perception-pipeline
pixi shell
source ros2_ws/install/setup.bash
ros2 bag play /media/adham/SSD1/linkou-2023-12-27-2-med/ --clock
```
