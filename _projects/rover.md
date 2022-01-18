---
title: 'Rover'
subtitle: 'Autonomous mobile robot, picking up anything in its path'
date: 2018-06-30 00:00:00
description: Mobile robot with 3DOF arm that drives around and picks stuff up and places it in a central clean up bin
featured_image: '/images/rover/rover_featured.jpg'
---

![](/images/rover/rover_featured.jpg)

## Robot Details

This robot consists of a mobile platform with 4 independent drive motors and a 3 degree-of-freedom robot arm attached to the front. The robot navigates around, avoiding large obstacles, until it finds an object that it is able to pick. It moves towards that object and uses the moutned arm to pick it up. The robot then returns the object to a pre-programmed location such as a basket for dog toys. 


<div class="gallery" data-columns="3">
	<img src="/images/rover/GizmoConcept.png">
	<img src="/images/rover/HoldingBall.JPG">
	<img src="/images/rover/TopView.JPG">
</div>


### Components

#### Controls
* [Raspberry Pi 4 B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/)
* [Arduino Mega](https://store.arduino.cc/products/arduino-mega-2560-rev3)

#### Sensors
* [9 Axis IMU BNO055](https://www.adafruit.com/product/2472)
* [Ultrasonic Proximity Sensor HC-SR04](https://www.raspberrypi.com/documentation/accessories/camera.html)
* [5MP Color Raspberry Pi Camera](https://www.raspberrypi.com/documentation/accessories/camera.html)

#### Power and Drive
* 7.4V LiPo Battery Packs
* LiPo Discharge and Charger Board
* Current and Voltage Monitor
* DC Brushed Motor with Encoder
* Mecanum Wheel and Hub Mount

#### Robot Arm
* Qty 4 20KG Annimos Digial Servos
* Serial Servo Driver Board
* Swash Plate Bearing


### Programming

<img src="/images/rover/vision-test.gif">
*Ball finding algorithm to identify and pick up tennis balls in the frame. 


## Pretty cool, huh?
<a href="https://jekyllthemes.io/theme/board-portfolio-jekyll-theme" class="button button--large">Follow Project</a>
