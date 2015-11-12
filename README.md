# Andbot_Speech

# Introduction
This is an example to use Google Speech Recognition activity to get Speech-to-Text, then use rosjava/android_core to send the speech text to the topic "MyPublisher/messages"

# How to test
* Build the code in Android Studio and run it
* In ROS machine, run **ifconfig** to get IP address of your ROS board
* In ROS machine, run **roscore**
* In another terminal of ROS machine, run **rostopic echo /MyPublisher/messages** to show recognized messages


# KNOWN ISSUES
* Everytime, when the app sent out the ROS topic message, it just crashed for unknown reason. 
