# Football Analysis Project

## Introduction
This project aims to detect and track players, referees, and footballs in a video using **YOLO**, one of the most advanced AI object detection models. We enhance performance through model training and use **KMeans clustering** for team assignment based on jersey colors.

Additionally, we:
- Measure **team ball possession** during a match.
- Use **optical flow** to analyze camera movement between frames.
- Implement **perspective transformation** to estimate real-world distances.
- Calculate **player speed and distance covered** using AI-driven tracking.

This project applies multiple machine learning and computer vision concepts, making it valuable for both beginners and experienced engineers.

## Features
- **Object Detection & Tracking**: Identifies and tracks players, referees, and footballs.
- **Team Identification**: Assigns players to teams based on jersey colors using KMeans clustering.
- **Ball Possession Analysis**: Computes possession percentages for each team.
- **Camera Movement Analysis**: Uses optical flow to track camera motion.
- **Real-World Distance Measurement**: Perspective transformation enables tracking in meters instead of pixels.
- **Speed & Distance Calculation**: Computes player movement statistics.

## Installation & Requirements
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- `ultralytics` (for YOLO model)
- `supervision` (for object tracking)
- OpenCV
- NumPy
- Matplotlib
- Pandas



