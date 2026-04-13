### Terminal 1 — Launch the perception pipeline:
<p>
bashcd /media/adham/SSD1/rse-3d-perception-pipeline <br>
pixi shell <br>
cd ros2_ws <br>
source install/setup.bash <br>
ros2 launch s1s2_r1_perception perception.launch.py <br>
</p>

### Terminal 2 — Play the bag:
<p>
bashcd /media/adham/SSD1/rse-3d-perception-pipeline<br>
pixi shell<br>
source ros2_ws/install/setup.bash<br>
ros2 bag play /media/adham/SSD1/linkou-2023-12-27-2-med/ --clock<br>
</p>
