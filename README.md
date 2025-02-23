# AI-Powered Universal Distress Signal Detection

## Overview

This project implements an AI-powered distress signal detection system that combines hand gesture and facial emotion recognition. The system first detects the universal distress hand gesture and then switches to analyzing facial expressions to identify the emotion of "fear." If both signals are detected, the system triggers a 911 emergency call using the Twilio API.

## Features

- **Hand Gesture Recognition**: Detects the universal distress signal, which consists of a consecutive open palm followed by a closed palm.
- **Facial Emotion Detection**: Analyzes facial expressions to identify fear.
- **Automated Emergency Call**: Initiates a 911 call when both distress signals (hand gesture and facial expression) are confirmed, using the Twilio API.
- **YOLOv8 Model for Object Detection**: Utilizes the YOLOv8 model for accurate and real-time distress signal recognition.

## Future Plans

- **PPG Integration**: Integrate heart rate monitoring through facial or wrist sensors to detect distress through physiological signals.
- **Enhanced Data Training**: Continuously improve the dataset with more real-world images, diverse scenarios, and edge cases.
- **Expanded Movement Tracking**: Add more advanced tracking algorithms to detect potential threats based on movement and posture.
- **Real-time Location Sharing**: Improve location-sharing features with more precise GPS tracking to provide better guidance to emergency responders.
- **Victim/Criminal Descriptions**: Implement a more sophisticated system for real-time description sharing with authorities, including physical details like clothing, height, and distinguishing features.

### Prerequisites

Python 3.9+

Install dependencies @ requirements.txt

Run detection script
python Combined_objdet.py
