# husky-exploration-launch
和huskey-exploration 一起使用，调用了husky-exploration 里面的文件

如果报错缺少velodyne 和 lms1xx 的依赖
可以
sudo apt-get install ros-melodic-velodyne

或者直接：
rosdep install --from-paths src --ignore-src --rosdistro=melodic -y
