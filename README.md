# Tr_DD-UrCtrl_RvizPlugin
A panel plugin for Rviz about Ur control


需要打开三个terminal
第一个terminal:
source ur3_ws/devel/setup.bash
roslaunch ur_gazebo new_world.launch

第二个terminal:
source ur3_treat/devel/setup.bash
rosrun rosrun ur_treatment main

第三个terminal:
source ur3_ws/devel/setup.bash
roslaunch ur3_moveit_config moveit_rviz.launch config:=true

rviz启动后点击左上角的panel，点击添加新的panel URPanel
