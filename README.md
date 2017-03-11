# startup
    xiaoqiang Ubuntu startup service  which launch groups of roslaunch files
##Usage:
###download to xiaoqiang ros workspace
```
cd ~/Documents/ros/src
git clone https://github.com/BlueWhaleRobot/startup.git
cd ..
catkin_make
```   
###Install this service into system, service name is startup
```
rosrun robot_upstart install startup/launch/startup.launch
```
###Uninstall this service
```
rosrun robot_upstart uninstall startup
```
### start this service manually
```
###download to xiaoqiang Documents
```
cd ~/Documents
git clone https://github.com/BlueWhaleRobot/stm32loader.git
```
###power on xiaoqiang chassis,start upgrade
```
cd stm32loader
sudo ./updateCarROM.sh
```

##Made with :heart: by BlueWhale Tech corp.


    小强底盘固件更新用脚本，mini和pro版通用
##使用方法:
###将软件包下载到小强Documents目录内
```
cd ~/Documents
git clone https://github.com/BlueWhaleRobot/stm32loader.git
```
###给小强底盘上电，开始固件升级
```
cd stm32loader
sudo ./updateCarROM.sh
```

##由蓝鲸科技精 :heart: 制作。
