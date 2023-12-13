# dof6-Arm
This project  including two parts: Mechanical Arm with Monocular Camera and Mechanical Arm with RGB-D Camera. The function of Mechanical Arm is as follows.

1. Object Detection using YOLOv5
2. Items classification 
3. Motion Planning



## Code Structure

Arm with Monocular Camera

```markdown
|-src
| |
| |-dofbot_config #assemble arm in MoveIt.
| |
| |-dofbot_description #describing arm and visualizing it using RVIZ.
| |
| |-dofbot_moveit #Motion Planning examples using MoveIt.
| |
| |-dofbot_msgs #msg, srv, action Interface.
| |
| |-dofbot_sensors #acquiring picture and publishing it.
```

Arm with RGB-D Camera

```markdown
|-src
| |
| |-dofbot_description #describing arm and visualizing it using RVIZ.
```

