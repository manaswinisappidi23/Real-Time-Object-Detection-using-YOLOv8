# 🎯 Real-Time Object Detection Using YOLOv8

## Overview

This project implements a real-time object detection system using the YOLOv8 (You Only Look Once) deep learning model. The application captures video from a webcam, detects multiple objects in real time, and displays bounding boxes with object labels and confidence scores.

YOLOv8 is one of the most advanced object detection algorithms, offering high accuracy and fast inference speed suitable for real-time applications.

## Features

- Real-time webcam object detection
- Detection of multiple objects simultaneously
- Bounding box visualization
- Object class labels
- Confidence score display
- Fast and efficient YOLOv8 inference
- Easy-to-use Python implementation

## Technologies Used

- Python
- OpenCV
- YOLOv8
- Ultralytics
- PyTorch
- NumPy

## Project Structure

YOLO_Object_Detection/

├── detect.py

├── requirements.txt

└── README.md

## Installation

### Clone the Repository

git clone https://github.com/manaswinisappidi23/Real-Time-Object-Detection-using-YOLOv8.git

### Navigate to Project Directory

cd Real-Time-Object-Detection-using-YOLOv8

### Install Dependencies

pip install -r requirements.txt

## Running the Project

Execute the following command:

python detect.py

The application will automatically:

1. Open the webcam
2. Load the YOLOv8 model
3. Detect objects in real time
4. Display bounding boxes and labels

Press **Q** to quit the application.

## Supported Object Classes

The pretrained YOLOv8 model can detect over 80 object categories, including:

- Person
- Car
- Bicycle
- Motorcycle
- Bus
- Truck
- Dog
- Cat
- Bird
- Laptop
- Mobile Phone
- Chair
- Bottle
- Book

and many more.

## Applications

- Smart Surveillance Systems
- Traffic Monitoring
- Autonomous Vehicles
- Security Systems
- Industrial Automation
- Wildlife Monitoring
- Retail Analytics

## Future Enhancements

- Custom Object Detection
- Animal Detection System
- Vehicle Counting
- Face Detection Integration
- Object Tracking
- Streamlit Web Dashboard
- CCTV Video Analysis
