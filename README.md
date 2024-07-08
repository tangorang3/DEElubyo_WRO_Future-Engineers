Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2022.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction

Introducing the DEElubyo bot, a self-driving robot made from Arduino components and electronic modules, designed to detect and avoid red and green obstacles. This innovative vehicle addresses critical societal issues like vehicle collisions caused by human error, distraction, and poor visibility. By integrating advanced sensors, microcontrollers, and intelligent algorithms, the DEElubyo bot navigates complex environments with precision, showcasing the potential of autonomous technology to reduce accidents and enhance road safety. This project underscores the importance of continuous technological development and education in creating safer, more efficient transportation systems, inspiring future engineers to tackle pressing industry challenges.

## Team Details

**Builder:** Dushiel A. Gelido       

**Coder:** Emmanuel Kristoffer O. Jacob

**Researcher:** Enraig G. Gacosta     

## Team Photo

**Official Photo**

**Funny Photo**

## Robot Design

**3D Model**

**Schematic Diagram**

https://github.com/tangorang3/DEElubyo_WRO_Future-Engineers/blob/d3efb20e911b70922056959647fb894ffa693feb/schemes/Screenshot%202024-07-08%20141758.png

**Actual Model**

## Materials (Components)

**Key Components of the DEElubyo Bot:**

**Connectors:**

Establish reliable electrical connections between the microcontroller and various electronic components/modules, ensuring efficient signal and power transmission.

**Breadboard:**

Allows temporary construction of circuits without soldering, facilitating easy testing and modification of designs.

**Battery Holder:**

Secures the battery in place, ensuring stable and consistent power supply to the robot.

**Ultrasonic Sensor:**

Detects and measures the distance to obstacles by emitting ultrasonic waves and calculating their return time, helping the robot navigate safely.

**Sensor Shield:**

Simplifies the connection of multiple sensors to the microcontroller, providing labeled ports for secure and organized wiring.

**Servo Motor:**

Controls the steering mechanism for precise adjustments to the front wheels' angle, enabling accurate directional changes.

**DC Motor:**

Drives the rear wheels, providing necessary torque and speed for the robot's movement.

**Motor Driver:**

Manages the DC motors' speed and direction, ensuring efficient and accurate response to the microcontroller's commands.

**IR Sensors:**

Detect specific colors on the mat by measuring reflected infrared light, allowing the robot to identify and respond to red and green obstacles.

**Buck Converter:**

Steps down the voltage from the battery to suitable levels for the microcontroller and other components, ensuring proper power distribution.

**Wheels:**

Enable the robot's movement, driven by the DC motors and steered by the servo motor.

**Acrylic Chassis:**

Provides a sturdy and lightweight frame to hold all the components together securely.

**Battery:**

Supplies power to all the robot’s components, ensuring consistent operation.

## Code

## How to prepare the repo based on the template

_Remove this section before the first commit to the repository_

1. Clone this repo by using the `git clone` functionality.
2. Remove `.git` directory
3. [Initialize a new public repository on GitHub](https://github.com/new) by following instructions from "create a new repository on the command line" section (appeared after pressing "Create repository" button).
