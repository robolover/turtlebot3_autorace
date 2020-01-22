# turtlebot3_autorace
2020 turtlebot3 autorace

[ERROR] [1579680090.027345]: bad callback: <bound method ImageCompensation.cbImageCompensation of <__main__.ImageCompensation instance at 0x7f0bf02c5638>>

Traceback (most recent call last):
  File "/opt/ros/kinetic/lib/python2.7/dist-packages/rospy/topics.py", line 750, in _invoke_callback
    cb(msg)
  File "/home/rms_edu_20/catkin_ws/src/turtlebot3_autorace_tunnel/turtlebot3_autorace_tunnel_camera/nodes/image_compensation", line 110, in cbImageCompensation
    alpha = (hist_size - 1) / input_range
ZeroDivisionError: integer division or modulo by zero

