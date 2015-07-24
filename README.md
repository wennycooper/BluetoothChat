# Android Remote Control for turtlesim

## Installations
* Install BluetoothChat.apk on both Tablet and Android phone
* On Android Setup, plz pair tablet & phone
* Install tcpServer project on ROS
* Run tcpServer on ROS by  (it will listen on 5001 port)
    rosrun [packageName] tcpServer
* Run turtlesim by
    rosrun turtlesim turtlesim_node
* Run BluetoothChat app on tablet & Android phone
* on Android phone, click 'discovery' icon to connect to Tablet via BT protocol
* Then, you can press [UP]/[DOWN]/[LEFT]/[RIGHT] buttons to control the turtle movements
