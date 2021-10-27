# icar_multi

> 本仓库为icar多机器人编队的ROS功能包

> 注意：本仓库需要icar功能包支持


## 使用

### 在计算机中仿真

#### 启动仿真环境
```
roslaunch icarmulti_gazebo 3robot.launch
```


#### 启动领航者的导航

```
roslaunch icarmulti_navigation nav_demo.launch
```

#### 启动跟随节点

```
roslaunch icarmulti_formation leader_follower.launch
```


![](images/icarmulti_leader.gif)