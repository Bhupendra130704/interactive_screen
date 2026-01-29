# Vision-Based Interactive Surface using Intel RealSense

## 📌 Overview
A portable computer-vision-based system that converts any flat surface into an interactive screen using an Intel RealSense depth camera and a projector. Hand gestures are tracked in real time and mapped to screen interactions.

## 🎯 Motivation
Large interactive displays are expensive and non-portable. This project demonstrates a low-cost, portable alternative using vision-based hand tracking for education, gaming, and HCI applications.

## 🛠 System Architecture
- Projector: Displays virtual interface on surface
- Intel RealSense D415: Captures RGB + depth
- MediaPipe: Hand landmark detection
- Coordinate Transformation: Maps 3D hand points to 2D screen
- Pygame: Interactive game interface

## 🔧 Hardware Used
- Intel RealSense D415
- Projector
- Laptop / PC

## 💻 Software Stack
- Python
- OpenCV
- MediaPipe
- pyrealsense2
- Pygame
- Multi-threading

## ⚙️ Features
- Real-time hand pose tracking (21 landmarks)
- 3D to 2D coordinate mapping
- Camera calibration
- Multi-threaded performance optimization
- Gesture-controlled Tic Tac Toe game
