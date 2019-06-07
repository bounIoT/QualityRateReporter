# QualityRateReporter
![A1](https://github.com/bounIoT/QualityRateReporter/blob/master/description.png)

## Problem Statement

* Crowdedness, air quality and temperature of the public places vary during time, and it is not possible for a user to know this information about the place beforehand
* When people go to public places such as libraries, shopping malls or museums, their experience might be affected greatly by these factors.
* In our university, there are many reported cases for people who can’t find a place to sit, or library is very cold that they can’t focus on their work.

## Problem Solution

* Ultrasonic sensors mounted at the entrances helps counting people coming in and out of the public places
* Humidity & Temperature sensors placed at various locations in the public place helps to obtain a general air quality measurement
* Gathering information from sensors and collecting them at the cloud, our mobil and web application can report detailed information about public place and an overall score calculated according to the user’s priorities

![A1](https://github.com/bounIoT/QualityRateReporter/blob/master/QualityRateReporter%20(1).png)
Iot architecture.

![A1](https://github.com/bounIoT/QualityRateReporter/blob/master/Schematic.png)
Schematic of our application.

## Demo
Here is a photo from demo.
![A1](https://github.com/bounIoT/QualityRateReporter/blob/master/demo.png)

### Used Open Source Libraries

* [NodeRed](https://nodered.org/)
* React Native

## Components

Component | Name | Action
---|---|---
Ultrasonic Sensor | HC-SR04  | Integration
Humidity & Temperature Sensor | DHT11 | Integration
Connectivity | Wifi and MQTT | Development (Relatively high energy consumption)
Embedded HW | Arduino YUN | Integration
Embedded SW | Arduino | Integration
Cloud Platform | IBM Cloud | Cloud Integration
Cloud SW | NodeJS | Cloud Integration
Mobile/Web Client SW | React Native | Integration
