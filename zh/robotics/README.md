# 机器人

机器人系统 API 允许通过飞行栈外的电脑环境，使用 [companion computer](../companion_computer/pixhawk_companion.md) 或其他环境 对 PX4 进行控制。 API 通过 [MAVLink](../middleware/mavlink.md) 或 [RTPS](../middleware/micrortps.md) 实现与 PX4 的通信。

Px4 可使用包括 [Dronecode SDK](https://www.dronecode.org/sdk/) 和 [ROS](../ros/README.md) 的机器人 API。 [DroneKit](../robotics/dronekit.md) 也可以用，但是优化不够好。