# Line-Following Robot

## Overview  
This project implements an autonomous **line-following robot** using **Arduino UNO** and **5 TCRT5000 infrared sensors**.  
The robot detects a high-contrast line on the ground and follows it automatically. Ideal for practicing sensor integration, motor control, and feedback loops.

## Hardware Used  
- **MCU:** Arduino UNO  
- **Line Sensors:** 5 × TCRT5000 infrared sensors  
- **Motor Driver:** L298N H-Bridge  
- **DC Motors + Robot Chassis & Wheels**  
- **Power Supply:** 12V battery pack   

## Software & Tools  
- **Language:** Arduino C/C++  
- **IDE:** Arduino IDE  
- **Algorithm:** Read 5 sensors → Calculate line deviation → Adjust motor speeds  
- **Motor Control:** PWM + H-Bridge  

## Features 
- Detect and follow a line automatically  
- 5-sensor array allows accurate detection of curves and forks  
- Adjust motor speeds for smooth turning  
- Stop when line ends (optional)  
- Expandable: obstacle avoidance, remote control

## Project Structure 
```
Line_following/
├─ version1.ino # Arduino UNO code version 1 (.ino)
├─ version2.ino # Arduino UNO code version 2 (.ino)
└─ README.md # This file
```

## Getting Started
```bash
git clone https://github.com/MinhQuocNguyenHoang/Line_following.git
cd Line_following/firmware
# Open the sketch in Arduino IDE
# Select Arduino UNO board, COM port
# Build & upload
```

## Future Improvements 🚀
- Implement PID control for smoother line following
- Add more intelligent fork/turn handling
- Integrate Bluetooth/WiFi for remote monitoring
- Encoder-based speed feedback for precision
- Obstacle avoidance integration

## Author
Nguyễn Hoàng Minh Quốc
GitHub: @MinhQuocNguyenHoang