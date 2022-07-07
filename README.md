# Work

1. The vehicle starts from position (0, 0) and cruises down a straight road in the x-direction. A static pedestrian is placed at position (60, 0) in the middle of the road. The vehicle uses LIDAR to detect the pedestrian and once the pedestrian is detected (Dsense ≤ d(t)), the vehicle will start braking at constant deceleration user provided. The vehicle will keep decelerating until its speed reaches 0.

2. Tried different values of the parameters Dsense, v0, ab, Treact and record corresponding d(t) after the vehicle is stopped. Compared the results from simulation with the invariants.

Steps:
1. source devel/setup.bash
2. roslaunch mp0 mp0.launch
3. cd catkin_ws/src/mp0/src
4. ~/catkin_amithr3/src/mp0/src$ python3 main.py --d_sense 15 --v_0 5 --a_b 5 --t_react 0.00
5. python main.py --x 0 --y 0

# Test

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/64373075/172037212-a31f7c49-24a2-4fe6-a2f1-1040f3702039.gif)

![Screenshot from 2022-07-06 22-14-55](https://user-images.githubusercontent.com/64373075/177683134-f0cdc3bf-49ee-4852-9c50-d64195299065.png)

