# Real-Time Human Detection & Counting System

This project is a real-time human detection and counting system built on Raspberry Pi using YOLO. It captures live video from a camera, detects people in each frame, counts them, and sends the detected person count to a web service through an API.

## Features

- Real-time human detection
- Live camera stream processing
- Human counting
- Raspberry Pi deployment
- API-based data transfer to a website or server
- Adjustable confidence threshold
- Resolution-based performance optimization

## Technologies Used

- Python
- Raspberry Pi
- YOLO
- OpenCV
- REST API

## Project Purpose

The purpose of this project is to detect and count people in a physical environment in real time using a lightweight embedded system. The detected count is then transmitted to a web platform so that the number of people can be monitored remotely.

## How It Works

1. The camera captures live video.
2. Each frame is processed using a YOLO model.
3. Human objects are detected in the frame.
4. The number of detected people is calculated.
5. The count is sent to a web API.
6. The website displays the current number of people.

## System Workflow

- Capture image from camera
- Run YOLO inference
- Filter only human detections
- Count detected people
- Display results locally
- Send count to external web service

## Example Use Cases

- Smart building monitoring
- Classroom occupancy tracking
- Office entry monitoring
- Store customer counting
- Embedded computer vision applications

## Installation

Clone the repository:

```bash
git clone https://github.com/borayilmaz12/human-detection-raspberrypi-yolo.git
cd human-detection-raspberrypi-yolo
