# Fast-Drone-250
This is a planner for **PX4 and Gazebo simulation**, where the planning part and controller come from [ZJU-FAST-Lab](https://github.com/ZJU-FAST-Lab/Fast-Drone-250).
I modified it to be used for PX4/Gazebo simulation. This migration can achieve **rapid migration between simulation and physical.**
# Achieve results
Here is result by use this code [video]( https://www.bilibili.com/video/BV1C2B2YrEfU/?share_source=copy_web&vd_source=694800f4f1ae99186a15066decbc1bc2)
<img src="https://github.com/user-attachments/assets/2379b1f9-1222-418b-a035-910554b53d3f" alt="image" width="300">
# How to use?
After starting the simulation (refer to [XTDrone](https://github.com/robin-shaun/XTDrone) )

**Take off and Hover**

`roslaunch px4ctrl multi_ctrl.launch`

**Start the Planning**

`roslaunch ego_planer multi_run_in_gazebo.launch` 
