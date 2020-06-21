# ros2_custom_msg
ROS2 Foxy custom MSG

This project is demonstrate how to create a custom message in ROS2 Foxy and work with python scripts with 
a Simnple Subscriber and Publisher.

I tried to get this information from other places but could not find proper way that describes this. 

The project has three packages. custom_msg_pub, custom_msg_sub, and custom_msgs

1. custom_msg_pub will publish custom messages using custom message from custom_msgs
2. custom_msg_sub will subscribe to the published custom messages.
3. custom_msgs package will define the custom message and installs them in install folder. 

How to Run
1. Clone the project
2. $ colcon build --simlinnk-install in rot folder.
3. $ source install/local_setup.bash (this will make the messages available during run time)
4. $ Runs subscriber and publisher
