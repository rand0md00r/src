1.安装
cd ~/catkin_ws/src/
git clone https://github.com/rand0md00r/navigation.git
cd ..
catkin_make_isolated


2.运行
2.1 在虚拟scout上运行
#新窗口
cd ~catkin_ws/
source devel/setup.bash
roslaunch scout_gazebo scout_gazebo.launch

#新窗口
cd ~catkin_ws/
source devel_isolated/setup.bash
cd ~catkin_ws/src/
roslaunch nav_run nav.launch


2.2 部署在小车上
TODO
