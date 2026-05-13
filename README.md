# Design And Development of Automated Mobile Robotic Arm Vehicle for Cold Storage Operations

## Final Year Mechanical Engineering Project

An automated mobile robotic arm designed for cold storage operations to reduce manual labor, improve safety, and increase operational efficiency in low-temperature environments.

<br>
<img width="750" height="789" alt="Final_Demontration" src="https://github.com/user-attachments/assets/196a4b28-c98e-495b-965a-36f447c25e5f" />
<br>

## Table of Contents

1. [Project Summary](#project-summary)  
2. [Project Overview](#project-overview)  
3. [System Architecture](#system-architecture)  
4. [Project Objectives](#project-objectives)  
5. [Engineering Relevance](#engineering-relevance)  
6. [Materials Used](#materials-used)  
7. [Software Used](#software-used)  
8. [CAD Design](#cad-design)  
9. [Components](#components)  
10. [Working Principle](#working-principle)  
11. [Project Development Process](#project-development-process)  
12. [Results](#results)  
13. [Applications](#applications)  
14. [Future Scope](#future-scope)  
15. [Skills Developed](#skills-developed)  
16. [Contributing](#contributing)  
17. [Author](#author)  
18. [Final Note](#final-note)

## Project Summary

The **Automated Mobile Robotic Arm Vehicle for Cold Storage Operations** is a final year mechanical engineering project focused on automating material handling tasks in cold storage environments. The system combines a mobile robotic platform with a robotic arm capable of pick-and-place operations using Arduino-based control and Bluetooth communication.

The project utilizes components such as MG995 servo motors, Arduino Uno, HC-05 Bluetooth module, L298N motor driver, and 3D printed mechanical parts designed in SolidWorks. The robotic system is developed to reduce manual labor, improve operational safety, and increase efficiency in low-temperature industrial environments.

This project integrates mechanical design, embedded systems, robotics, CAD modeling, and automation technologies into a practical industrial application.

## Project Overview

The **Automated Mobile Robotic Arm Vehicle for Cold Storage Operations** is a final year mechanical engineering project designed to automate material handling tasks in cold storage environments. The system combines a mobile robotic platform with a robotic arm capable of performing pick-and-place operations through wireless Bluetooth control.

The project uses components such as Arduino Uno, MG995 servo motors, HC-05 Bluetooth module, L298N motor driver, and 3D printed mechanical parts. The main objective is to reduce manual labor, improve worker safety, and increase operational efficiency in low-temperature storage facilities through robotic automation.

## Project Focus

The main focus of this project is:
- Automation in cold storage environments
- Mobile robotics
- Robotic arm manipulation
- Wireless robotic control
- Embedded systems integration
- Mechanical system design

# Project Objectives

- Reduce manual labor in cold storage
- Improve operational safety
- Develop an automated handling system
- Enable wireless robotic control
- Design a low-cost automation solution
- Improve material transportation efficiency

## Certificate of Journal and Conference

### Journal Publication Certificate

This project research work was successfully published/presented in a reputed engineering journal based on robotics, automation, and cold storage applications.

#### Research Area
- Robotics and Automation
- Cold Storage Automation
- Embedded Systems
- Mobile Robotic Arm
- Industrial Automation

#### Published Research Title
**Development of Automated Mobile Robotic Arm Vehicle for Cold Storage Operations**

#### Journal Details
| Details | Information |
|---|---|
| Journal Name | IRJMETS |
| Paper ID |IRJMETS70400360229 |
| Volume | 07 |
| Issue | 04 |
| Publication Year | 2026 |
| ISSN Number | 2582-5208 |
| DOI | https://www.doi.org/10.56726/IRJMETS75091 |


### Conference Presentation Certificate

The project was also presented at a technical conference/seminar related to engineering innovation and automation technologies.

#### Conference Presentation Title
**Development of Automated Mobile Robotic Arm Vehicle for Cold Storage Operations**

#### Conference Details

| Details | Information |
|---|---|
| Conference Name | International Conference on Recent Advances in Engineering and Sciences – 2025 (ICRAES-2K25) |
| Organized By | Bharati Vidyapeeth’s College of Engineering, Lavale, Pune |
| Presentation Type | Technical Paper Presentation |
| Conference Year | 2025 |
| Location | Pune, India |


## Certificate Images

### Journal Certificate
<BR>
<img width="758" height="1064" alt="Journal_Certificate" src="https://github.com/user-attachments/assets/0fd2f46a-48ff-401b-b4cd-58cfcab7e322" />
<BR>

### Conference Certificate
<BR>
<img width="1503" height="1078" alt="Conference_Certificate" src="https://github.com/user-attachments/assets/53c99faa-2fab-4f77-a15c-db145180aab8" />
<BR>

## Hardware Components

| Sr No | Component | Specification |
|------|------------|---------------|
| 1 | Servo Motor | MG995 High Torque Servo |
| 2 | Micro Servo | SG90 |
| 3 | Controller | Arduino Uno |
| 4 | Servo Controller | USB Bluetooth 18 Servo Controller |
| 5 | Motor Driver | L298N |
| 6 | Bluetooth Module | HC-05 |
| 7 | Battery | Samsung 7.4V 2600mAh Li-Ion |
| 8 | Stepper Motor | NEMA Stepper Motor |
| 9 | Bearings | 606ZZ / 608ZZ |
| 10 | Wheels | Robotic Wheels |

## Software Used

- Arduino IDE
- SolidWorks
- Tinkercad
- RoboKits Servo Controller Software
- FlashPrint

## Materials Used

| Material | Purpose |
|---|---|
| PLA Filament | 3D Printed Parts |
| Aluminum Frame | Structural Support |
| Rubber Wheels | Mobile Movement |
| Bearings 606ZZ / 608ZZ | Smooth Rotation |
| Servo Mounts | Joint Assembly |

## Engineering Calculations

### Payload Capacity

- Expected Payload = 100 g
- Safety Factor = 1.5
- Safe Payload = 150 g

### Torque Calculation

Formula:

```math
T = F × r
```

Calculated Torque:
- Force = 1.962 N
- Torque = 0.981 N·m
- Equivalent Torque ≈ 10 kg/cm

### Power Consumption

```math
P = V × I
```

- Voltage = 6V
- Current = 2.5A
- Total Power = 45W

### Battery Backup

- Battery Energy = 19.24 Wh
- Estimated Backup = 26 Minutes

## CAD Design

The robotic arm and chassis were designed using **SolidWorks**.

Designed Components:
- Robotic arm links
- Gripper mechanism
- Servo mounts
- Mobile chassis
- Wheel assembly

The CAD models were exported as STL files for 3D printing.

## Working Principle

1. User sends command via Bluetooth.
2. HC-05 module receives data.
3. Arduino processes the command.
4. Servo controller drives robotic arm motors.
5. L298N controls wheel movement.
6. Robotic arm performs handling operation.

## Project Development Process

### Step 1 — Requirement Analysis
- Studied cold storage operational problems
- Identified automation requirements

### Step 2 — CAD Modeling
- Designed robotic arm in SolidWorks
- Created assembly and motion design

### Step 3 — 3D Printing
- Converted STL files
- Printed mechanical components

### Step 4 — Electronics Integration
- Connected Arduino and motor drivers
- Installed Bluetooth communication system

### Step 5 — Programming
- Developed Arduino control code
- Implemented motor movement logic

### Step 6 — Testing
- Tested robotic arm movement
- Checked wireless communication
- Performed cold condition trials

## Results

- Successful robotic movement
- Stable Bluetooth communication
- Reliable pick-and-place operation
- Accurate servo control
- Efficient mobility in testing conditions

## Applications

- Cold storage warehouses
- Industrial automation systems
- Smart logistics and material handling
- Food and pharmaceutical storage facilities
- Hazardous environment operations

## Skills Developed

- SolidWorks CAD Modeling
- 3D Printing
- Basic Arduino Programming
- Embedded Systems
- Robotics Integration
- Mechanical Assembly
- Engineering Design

## Contributing

Contributions, suggestions, and improvements related to CAD modeling, simulation, robotic arm control, and automated mobile robotic system design for cold storage applications are welcome. Feel free to fork the repository and submit pull requests for enhancements.

## Future Improvements

- AI-based navigation
- Computer vision integration
- IoT monitoring system
- Implementation of autonomous navigation using SLAM
- AI-based object detection for intelligent picking
- IoT-based monitoring system
- Fully automated charging station integration
- Multi-robot coordination for warehouse automation
- Obstacle avoidance system

## Author

**Utkarsh Jadhav**  
Mechanical Engineering Student | CAD Designer | Robotics Enthusiast  

- GitHub: https://github.com/utkarsh-jadhav-mech
- LinkedIn: https://www.linkedin.com/in/utkarsh-jadhav-mech

### Team Members
- Girish Patil
- Subodh Bhosale
- Sunil Dhargude
- Omkar Pore

### Guided By
**Prof. S. H. Kumbhar** 

## Final Note

This project represents an integration of mechanical design, electronics, and automation for cold storage applications. It demonstrates the practical implementation of a mobile robotic arm system aimed at improving efficiency, safety, and productivity in industrial environments.

Continuous improvements and innovative ideas are always encouraged to enhance the performance and real-world applicability of this system.
