# motionCtrlTeleopNode
tele-operation for manipulating movable robots under ROS 1. It publishes geometry_msgs/Twist Message with user defined topic(defualt: cmd_vel)

## Manipulating keys definition
![Untitled Diagram drawio](https://user-images.githubusercontent.com/72239958/202851886-e404eafc-dae1-488b-bbb4-356eb4cca441.png)

## Engineering maintainance keys defintion
| Key | Function                                         |
|-----|--------------------------------------------------|
| 0   | neutralize all engineering operation             |
| 3   | print the yaw value of IMU                       |
| 4   | reset the IMU                                    |
| 5   | print the value of encoder                       |
| 6   | reset the value of encoder                       |
| 7   | calibrate the map between reference and PWM duty |
| 8   | clear calibration results                        |
