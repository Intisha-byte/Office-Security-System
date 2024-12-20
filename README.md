# Office Security System Using Raspberry Pi
## Introduction
In today’s interconnected corporate environment, a robust office security system is essential to protect workplaces, assets, and employees from physical and cyber threats. This project leverages Raspberry Pi 3, Pi Camera, PIR Motion Sensor, LED, and Buzzer to create a cost-effective security solution. By integrating technologies such as real-time monitoring via Real VNC Viewer, motion detection, and audible alerts, the system ensures a safe and productive work environment while providing peace of mind to employees and stakeholders alike.
## Features
- Motion Detection: Detects unauthorized movement using a PIR motion sensor.
- Visual and Audible Alerts: Triggers LED and buzzer alarms upon detecting motion.
- Real-Time Surveillance: Captures images and videos using the Pi Camera.
- Remote Monitoring: Access live camera feed via Real VNC Viewer from anywhere.
- Cost-Effective Solution: Provides security without the need for expensive equipment.
- Scalable Design: Easily extendable for larger office spaces.
## Hardware and Software Requirements
### Hardware:
- Raspberry Pi 3
- Pi Camera
- PIR Motion Sensor
- LED
- Buzzer
- Connecting Wires
- Breadboard (optional for prototyping)
### Software:
- Python 3
- Required Python Libraries: RPi.GPIO, picamera, time
- Real VNC Viewer
- Raspbian OS (latest version)
## Installation
1. Clone the Repository
git clone https://github.com/your-username/office-security-system.git
cd office-security-system
2. Install Dependencies
Install required Python libraries:
pip install RPi.GPIO picamera
3. Hardware Setup
Connect the PIR sensor, LED, and buzzer to the Raspberry Pi GPIO pins as per the wiring diagram provided in the repository.
Attach the Pi Camera to the camera port on the Raspberry Pi.
4. Configure Real VNC Viewer
Enable VNC on Raspberry Pi through raspi-config.
Set up VNC Viewer on your remote device and connect to the Raspberry Pi.
## Usage
1. Start the System
Run the main script:
python security_system.py
2. Monitor Alerts
Observe real-time alerts via LED and buzzer when motion is detected.
Access live video feed through Real VNC Viewer for remote monitoring.
3. Stop the System
Terminate the script by pressing Ctrl+C in the terminal.
## System Architecture
- PIR Motion Sensor: Detects motion and sends signals to the Raspberry Pi.
- Raspberry Pi: Processes the signal, triggers alerts, and controls the Pi Camera.
- Pi Camera: Captures images or video footage upon motion detection.
- LED and Buzzer: Provide visual and audible alerts for detected activity.
- Real VNC Viewer: Enables remote access to the system for live monitoring.
## Troubleshooting
- No Alerts: Check sensor connections and ensure GPIO pins are configured correctly in the script.
- Camera Not Working: Verify the Pi Camera is enabled in raspi-config and securely connected.
- VNC Connection Issues: Ensure both devices are on the same network or use VNC cloud connectivity.
## Acknowledgments
Raspberry Pi Foundation for their documentation.
Open-source Python libraries.
Community forums for troubleshooting guidance.
## Contact
For questions or feedback, contact: Intisha Munawwar Khot.
