# dynamixel_motor

ROS stack for interfacing with Robotis Dynamixel line of servo motors.

The branch `faster_rate` provides the following changes:

- The waiting delays are reduced
- The state provides only the current position
- The `queue_size` parameters have an explicit `1` value
- Added the dependencies to build the messages first
