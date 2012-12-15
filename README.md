
## This is a "hello world" example for communicating from ROS<->Erlang.

- It uses Python as the "glue".  
- On the ros side, it uses rospy.  
- On the erlang side, it uses py-interface.

## How it works
 
This python process subscribes to a ROS topic, and forwards whatever it
receives to an Erlang node via py-interface

## Dependencies

- ros
- rospy (ships with ros)
- turtlesim (ships with ros)
- erlang
- py-interface (http://www.lysator.liu.se/~tab/erlang/py_interface/)

## Building

Nothing to build aside from dependencies

## Running

./hello_ros_erlang.sh
