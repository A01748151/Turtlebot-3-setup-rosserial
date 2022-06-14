# Turtlebot-3-setup-rosserial

In this project will be explained the process for configurating ubuntu software to comunicate with turtlebot3 by using rosserial.
The project will follow this order:
1. Installation of Arduino IDE on linux Ubuntu
2. Installation of the rosserial Ubuntu
3. Installation of dinamixels and further configuration


## Installation of Arduino IDE in linux Ubuntu
#### Update packages
$ sudo apt-get update\
$ sudo apt-get upgrade

#### Download arduino IDE and extract it from https://www.arduino.cc/en/Main/Software
Another procedure to do this step is to paste the following commands in the terminal:
$ mkdir arduino\
$ cd arduino/\
$ wget https://downloads.arduino.cc/arduino-1.8.15-linux64.tar.xz

Note: The wget command downloads the arduino version 1.8.15 tar.xz, if you want another version, change just the version number.

The following commands extracts the file

$ tar -xvf ./arduino-1.8.15-linux64.tar.xz

And finally we move to the file inside the extracted folder and execute the installation

$ cd arduino-1.8.15/
$ sudo ./install.sh


This following commands will provide the necessary tools to anable the communication with the opencv board by using arduino IDE

## Installation of rosserial
There are 3 commands needed to start working with rosserial
#### sudo apt-get install ros-noetic-rosserial-arduino
![image](https://user-images.githubusercontent.com/42352941/173672548-b1b5fc0d-82e1-49e6-af3b-705e03843792.png)


#### sudo apt-get install ros-noetic-rosserial
![image](https://user-images.githubusercontent.com/42352941/173672569-eaa97ee0-6679-4e10-af2e-304b46b4d898.png)


#### sudo apt-get install ros-noetic-rosserial-server
![image](https://user-images.githubusercontent.com/42352941/173672602-a093afeb-9501-4d63-a473-c510e144ebad.png)

## Installation of dinamixels and further configuration

In order to install dinamixels library is important to use the following commands

#### sudo apt install ros-noetic-dynamixel-sdk
![image](https://user-images.githubusercontent.com/42352941/173675503-94c24ffe-a043-4689-976c-c34196bb0e8a.png)


#### sudo apt install ros-noetic-turtlebot3-msgs
![image](https://user-images.githubusercontent.com/42352941/173675534-87e58d18-3578-4b9c-8b28-48812cb9f64d.png)


#### sudo apt install ros-noetic-turtlebot3
![image](https://user-images.githubusercontent.com/42352941/173675553-62290ef7-1748-4a84-8f9b-8b2ed8e8fca4.png)
