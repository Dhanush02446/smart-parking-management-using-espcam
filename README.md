About the Project
This project is a smart parking management system built using an ESP32-CAM and TinyML (Edge Impulse).
It detects whether parking slots are occupied or free using a camera and shows the status live on a Blynk IoT dashboard.
The system uses image-based detection instead of multiple physical sensors, making it a low-cost and scalable solution.

How It Works..
1. The ESP32-CAM captures images of the parking area.
2. A machine learning model trained using Edge Impulse runs directly on the device.
3. The model detects visual markers:
   - Circle represents Parking Slot 1.
   - Star represents Parking Slot 2.
4. Based on detection confidence, each slot is marked as OCCUPIED or EMPTY.
5. The parking status is updated in real time on the Blynk mobile application.

Key Features
- Camera-based parking slot detection
- On-device TinyML inference
- Real-time IoT monitoring using Blynk
- LED and text indicators for parking status
- Low-cost embedded solution

Hardware Used
- ESP32-CAM (AI Thinker module)
- FTDI Programmer
- Power supply
- Parking slot prototype or visual markers

Software and Tools
- Arduino IDE
- Edge Impulse SDK
- ESP32 Camera Library
- Blynk IoT Platform
- Embedded C/C++

Machine Learning Details
- Model trained using Edge Impulse
- Deployed directly on ESP32-CAM
- Supports image classification and object detection
- Confidence thresholds used for reliable detection

IoT Dashboard
- Live parking slot status shown on Blynk app
- LED widgets indicate occupied or empty slots
- Text widgets display clear parking information

Project Structure
smart-parking-management-esp32cam/
src/
main.ino
edge-impulse-model/
README.md

Future Improvements
- Support for more parking slots
- Vehicle number plate recognition
- Web-based dashboard
- Cloud data logging
- Push notifications
