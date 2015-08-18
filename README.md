# dynamixel_motor

ROS stack for interfacing with Robotis Dynamixel line of servo motors.

The branch `faster_rate` provides the following changes:

- The waiting delays are reduced
- Used the `SYNC_READ` special instruction of the USB2AX
- The state provides only the current position
- The `queue_size` parameters have an explicit `1` value
- Added the dependencies to build the messages first

**WARNING: works only with the USB2AX, not with the USB2Dynamixel!**
