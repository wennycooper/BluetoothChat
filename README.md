# Android Remote Control for turtlesim

# What?
* This is a project to control ROS robot by Android phone

# Hardware Configurations
* You will need three hardware components, a ROS board, an Android tablet and an Android phone
* Android phone will send commands to Android tablet via BT protocol
* Then, Android tablet will forward commands to ROS board via TCP socket communication

# Installations
* Install BluetoothChat.apk on both Tablet and Android phone
* On Android Setup, plz pair tablet & phone
* Install tcpServer project on ROS board
* Run tcpServer on ROS by  (it will listen on 5001 port)

        rosrun [packageName] tcpServer
        
* Run turtlesim by

        rosrun turtlesim turtlesim_node
        
* Run BluetoothChat app on tablet & Android phone
* on Android phone, click 'discovery' icon to connect to Tablet via BT protocol
* Then, you can press [UP]/[DOWN]/[LEFT]/[RIGHT] buttons to control the turtle movements
