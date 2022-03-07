1.安装

    cd navigation_ws/
    git clone https://github.com/rand0md00r/src.git
    catkin_make_isolated

2.运行
2.1 在虚拟scout上运行

    #新窗口
    cd navigation-ws/
    source devel_isolated/setup.bash
    roslaunch scout_gazebo scout_gazebo.launch

    #新窗口
    cd navigation-ws/
    source devel_isolated/setup.bash
    cd src/
    roslaunch nav_run nav.launch


2.2 部署在小车上

    TODO
