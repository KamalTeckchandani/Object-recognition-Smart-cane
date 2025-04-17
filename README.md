Object Recognition System Integrated with a Smart Cane
Overview
This project is a Smart Cane developed to assist visually impaired individuals by detecting nearby obstacles and recognizing objects in their path. The system combines ultrasonic sensors, Arduino logic, Bluetooth communication, and a camera module connected to a smartphone application for real-time object recognition and voice feedback.

Features
🔊 Obstacle Detection
Equipped with ultrasonic sensors that continuously monitor the surroundings. If an object is detected within a specific range, the cane responds with a vibration and/or buzzer alert to notify the user.

📸 Object Recognition via Smartphone App
A mounted camera on the cane captures an image when a button is pressed. The image is transmitted via Bluetooth to a custom Camera APK installed on a smartphone.

🧠 AI-Based Object Detection
The smartphone app processes the image using an object recognition algorithm, and the name of the detected object is spoken out loud, helping the user identify what's in front of them.

🔗 Bluetooth Connectivity
Wireless communication enables smooth interaction between the cane's hardware and the mobile application.

Technologies Used
Arduino Uno: Microcontroller for sensor and component management.

Ultrasonic Sensors: Measure distance to obstacles.

Vibration Motor & Buzzer: Provide physical and auditory alerts.

Camera Module: Captures images on demand.

Bluetooth Module: Sends images to smartphone.

Android (Camera APK): Receives image, processes it, and speaks out the identified object.

Object Recognition (OpenCV/ML): Implemented in the APK to identify and label objects.

How It Works
Obstacle Detection

The ultrasonic sensor detects any object within a set distance.

The Arduino triggers a vibration or sound alert to warn the user.

Object Recognition

The user presses a button to activate the camera.

The camera captures an image and sends it to the smartphone app via Bluetooth.

The Camera APK processes the image using an object recognition model, Firebase and uses text-to-speech to speak the object name.

Applications
Assists visually impaired individuals in understanding and navigating their environment.

Can be expanded into smart mobility and home navigation tools.

Future Enhancements
GPS-based location awareness.

Real-time video streaming and recognition.

Voice command and AI assistant integration.
