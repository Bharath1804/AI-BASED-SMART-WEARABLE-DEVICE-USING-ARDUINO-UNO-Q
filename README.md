# AI-Based Smart Wearable Device Using Arduino UNO Q

## Project Overview

This project presents an **AI-Based Smart Wearable Device** designed to assist visually impaired individuals with safer and more independent navigation. The system uses the **Arduino UNO Q** as the main embedded platform and integrates **YOLO-based object detection**, **ultrasonic distance sensing**, and a **multi-beep alert system** to provide real-time environmental awareness.

The device detects surrounding objects such as people, vehicles, chairs, bottles, and other obstacles. It also measures the distance between the user and nearby objects using an ultrasonic sensor. Instead of using voice feedback, the system provides non-verbal alerts through different beep patterns, helping the user understand object proximity and potential hazards quickly.

## Key Features

- Real-time object detection using YOLO
- Arduino UNO Q-based wearable assistive system
- Ultrasonic sensor for obstacle distance measurement
- Cloud-assisted computer vision processing
- Multi-beep alert system for hazard warning
- Web UI for real-time monitoring and debugging
- Compact helmet-mounted wearable prototype
- Low-cost and practical assistive navigation solution

## Hardware Components

- Arduino UNO Q
- Full HD USB Webcam
- 3V Ultrasonic Sensor
- 5V Piezoelectric Buzzer
- USB Hub
- 10000 mAh Power Bank
- Protective Helmet
- Connecting wires and mounting accessories

## Software Components

- Arduino App Lab
- YOLO Object Detection Model
- Python
- Arduino C/C++ Sketch
- Web UI using HTML and CSS
- Bridge API for communication between Linux MPU and MCU

## System Working

The camera mounted on the wearable device captures real-time video frames from the user’s surroundings. These frames are processed using the YOLO object detection model to identify objects in the environment. At the same time, the ultrasonic sensor measures the distance of nearby obstacles.

The system combines object classification and distance measurement to determine the level of risk. If an object is detected within a safe range, the device remains idle or produces slow beeps. If the object moves closer, the beep frequency increases. When the object reaches a critical distance, the buzzer produces rapid high-frequency beeps to warn the user immediately.

## Alert Logic

- **Safe Range:** Slow or no beep
- **Caution Range:** Medium-frequency beep
- **Critical Range:** Fast and high-frequency beep
- **Object-Specific Alerts:** Different beep patterns can be assigned to different detected objects

## Results

The prototype successfully detected multiple objects in real time and generated appropriate beep alerts based on object type and distance. The ultrasonic sensor provided accurate proximity information, while the Web UI displayed detected objects with labels and bounding boxes. The multi-beep feedback system offered an intuitive and simple way to alert the user without relying on speech output.

## Applications

- Assistive navigation for visually impaired individuals
- Smart wearable safety devices
- Obstacle detection systems
- Embedded AI and IoT-based assistive technology
- Real-time computer vision applications

## Future Improvements

- Improve object detection accuracy using optimized AI models
- Add offline processing support for better reliability
- Integrate vibration feedback for silent alerts
- Improve battery efficiency and wearable comfort
- Add GPS-based navigation support
- Develop a mobile application for user settings and monitoring

## Conclusion

The AI-Based Smart Wearable Device demonstrates how embedded systems, artificial intelligence, and sensor fusion can be combined to support visually impaired users. By using the Arduino UNO Q, YOLO object detection, ultrasonic sensing, and a multi-beep alert system, the project provides a practical and affordable solution for improving mobility, safety, and situational awareness.

## Author

**Bharath Kumar Medi**  
Department of Electrical and Computer Engineering  
University of Alabama at Birmingham  
Birmingham, USA

