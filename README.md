# Andbot_Speech

# Introduction
This is an example to use Google Speech Recognition activity to get Speech-to-Text, then use rosjava/android_core to send the speech text to the topic "MyPublisher/messages"

# How to test

* In ROS machine, run **ifconfig** to get IP address of your ROS board
* In ROS machine, run **roscore**
* In another terminal of ROS machine, run **rostopic echo /MyPublisher/messages** to show recognized messages
* Build the code in Android Studio and run it
* In Android phone, type-in your ROS board IP address, and click CONNECT button
 * Then click **SPEECH** button,  say something to it
* Then check the output in the terminal of running rostopic echo  

# KNOWN ISSUES
* Everytime, when the app sent out the ROS topic message, it just crashed for unknown reason. 
