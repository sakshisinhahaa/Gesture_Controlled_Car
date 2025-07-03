# Gesture_Controlled_Car
A gesture-controlled robot car that moves and varies its speed based on hand tilt. It uses the MPU6050 accelerometer and gyroscope sensor to detect hand gestures and transmits commands wirelessly via the HC-05 Bluetooth module to the robot car.

# Features
● Hand gesture-based control (forward, backward, left, right)

● Speed variation based on tilt angle

● Wireless communication using Bluetooth (HC-05)

● Real-time control without physical contact

# How It Works
1. The MPU6050 mounted on a glove detects the orientation of your hand.
  
2. The Arduino processes the tilt angles and sends corresponding commands over
Bluetooth.

3. The robot car receives these commands and moves accordingly, adjusting speed
based on tilt.

# Control Mapping
| Hand Gesture   | Action        |
| -------------- | ------------- |
| Tilt Forward   | Move Forward  |
| Tilt Backward  | Move Backward |
| Tilt Left      | Turn Left     |
| Tilt Right     | Turn Right    |
| Neutral (Flat) | Stop          |


