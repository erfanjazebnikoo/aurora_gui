# Aurora - GUI

GUI application of [Aurora][aurora_core] project. [Aurora][aurora_core] is an program of autonomous multirotor robots based on APM autopilot. We use [ROS platform][ros] and [Mavlink protocol][mavlink-wiki] for connection between program and robot.
A multirotor or multicopter is a rotorcraft with more than two rotors. An advantage of multirotor aircraft is the simpler rotor mechanics required for flight control. 
We designed, optimized and manufactured hexacopter drone with a [vision based][aurora_vision] AI and [online 3D mapping][aurora_copter] using the C++ programming language on [ROS platform][ros].

-------------------

### Installation Requirements

| Requirement | Tested Successfully On |
| ------ | ------ |
| OS| [Ubuntu 14.04](http://cdimage.ubuntu.com/netboot/14.04/?_ga=2.72803859.1606487436.1539181592-1947134802.1539181592)|
| Programming Language| C++11|
| Framework| [Qt 5.0][qt]|
| ROS | [ROS indigo][ros-indigo]|
| Flight Control| [Ardupilot Mega (APM) 2.8][apm]|
| Ground Control Station Communication|[MAVROS][mavros], [wiki][mavros-wiki]|
| Auto Pilot Communication| [Mavlink][mavlink], [wiki][mavlink-wiki]|

-------------------

## Software
The Aurora software section divides into: 

| Application | Link |
| ------ | ------ |
| Core | [https://github.com/erfanjazebnikoo/aurora_core][aurora_core] |
| GUI| [https://github.com/erfanjazebnikoo/aurora_gui][aurora_gui] |
| Vision| [https://github.com/SajjadRahnama/aurora_vision][aurora_vision] |
| Mapping| [https://github.com/SajjadRahnama/aurora_copter][aurora_copter] |

[GUI][aurora_gui] is responsible for receiving inputs from the drone and controlling it, [Core][aurora_core] responsibility is to receive inputs from [GUI][aurora_gui], analyze data and provide proper outputs for the drone, and [The Mapping application][aurora_copter] is responsible for making 3D maps from coordinates and aerial images.
In this project C++ programming language, [OpenCV][opencv] and [QT][qt] libraries are applied. [QT5][qt] libraries and ROS packages along with other libraries respectively used in all applications.

![N|Solid](http://erfanjazebnikoo.com/downloads/aurora-core-gui.jpg)

-----------------

## Support

- [Erfan Jazeb Nikoo](mailto:erfan.jazebnikoo@gmail.com)
- [Sajjad Rahnama](mailto:sajjadmuscle@gmail.com)

[pixhawk]:<https://docs.px4.io/en/flight_controller/pixhawk4.html>
[mavros]:<https://dev.px4.io/ros-mavros-installation.html>
[mavros-wiki]:<http://wiki.ros.org/mavros>
[mavlink]:<http://qgroundcontrol.org/mavlink/>
[mavlink-wiki]:<http://wiki.ros.org/mavlink>
[ros]:<http://www.ros.org/core-components/>
[ros-indigo]:<http://wiki.ros.org/indigo/Installation/Ubuntu>
[pid]:<https://en.wikipedia.org/wiki/PID_controller>
[gps]:<https://www.u-blox.com/en/product/neo-m8-series>
[motors]:<http://store-en.tmotor.com/>
[RFM23Bp]:<http://www.hoperf.com/upload/rf/RFM23BP.pdf>
[openLRSng]:<https://openlrsng.org/>
[rbpi3]:<https://www.raspberrypi.org/products/raspberry-pi-3-model-b/>
[opencv]:<https://opencv.org/>
[qt]:<https://www.qt.io/>
[aurora_gui]:<https://github.com/erfanjazebnikoo/aurora_gui>
[aurora_core]:<https://github.com/erfanjazebnikoo/aurora_core>
[aurora_copter]:<https://github.com/SajjadRahnama/aurora_copter>
[aurora_Vision]:<https://github.com/SajjadRahnama/aurora_vision>
[apm]:<http://www.ardupilot.co.uk/>
