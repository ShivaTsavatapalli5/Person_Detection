# Person Detection Using Google Coral

## Overview
This project implements real-time person detection using a TensorFlow Lite model optimized for the Google Coral USB Accelerator. The system is capable of processing live video feeds for detecting people, achieving high accuracy and performance.

## Hardware
- **Camera**: Captures the live video feed.
- **Google Coral USB Accelerator**: Provides fast inference capabilities, significantly boosting detection speed.
- **Raspberry Pi 4B+**: Handles the processing of the video stream and the detection logic.

## Model and Performance
- **Model Type**: TensorFlow Lite model optimized for Edge TPU.
- **Accuracy**: Achieved a maximum of **92% accuracy** in person detection.
- **Frame Rate**: Capable of processing at **32 frames per second (FPS)**, ensuring real-time detection.

## Usage
- **Real-time Detection**: The system processes the camera feed in real time, detecting persons with high accuracy and low latency thanks to the Coral USB Accelerator.

## Steps to install required libraries and files
- Note:- Make Sure that git for windows installed
     ```bash
     git clone https://github.com/ShivaTsavatapalli5/Person_Detection.git
     cd Person_Detection
     ./requirements.sh
     ```
