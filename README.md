# arduino_radar-
Arduino radar / 180° ultrasonic scanner using HC-SR04 + servo — Arduino sketch + Processing visualization

Project Overview:
This project involves creating a functional radar system using an ultrasonic sensor, Arduino Uno, and a breadboard.
The radar is capable of detecting objects within a specified range and displaying their positions on a graphical interface.
It is a cost-effective way to learn about radar technology and its basic principles.

Components Required:
-Ultrasonic Sensor (e.g., HC-SR04): Measures the distance to objects by emitting ultrasonic waves and detecting the reflected signals.
-Arduino Uno: Acts as the microcontroller to process data and control the system.
-Servo Motor: Rotates the ultrasonic sensor to cover a wide area for scanning.
-Breadboard and Jumper Wires: Used for creating the circuit connections.
-Computer and Software: To visualize the radar data on a graphical interface, like Processing or Python.


Working Principle:
1. Object Detection:
The ultrasonic sensor emits sound waves and calculates the time taken for the echo to return after bouncing off an object.

2. Rotation and Scanning:
A servo motor rotates the sensor in a predefined angle range (e.g., 0° to 180°).
Distance data is collected at each angle to map the surroundings.

3. Data Visualization:
The Arduino sends the distance and angle data to a computer via serial communication.
The data is displayed on a radar-like interface, showing the positions of detected objects.
