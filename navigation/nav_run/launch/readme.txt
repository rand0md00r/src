				
launch文件名		|类型	|说明
nav.launch		|必要	|运行指令：
			|	|cd ~/navigation_ws/src
			|	|roslaunch nav_run nav.launch
read_map.launch	|必要	|读取建图模式下的二维地图
scout_gmapping.launch	|必要	|开启gmapping
			|	|
amcl.launch		|非必要	|自适应蒙特卡洛，用于全局定位
hector_slam.launch	|非必要	|用于建图
hector_slam_demo.launch|非必要	|
save_map.launch	|非必要	|保存地图

