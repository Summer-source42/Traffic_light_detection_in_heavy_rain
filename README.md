# Traffic Light and Traffic Signs Detection in Heavy Rainy Weather

## Project Overview

This project is designed to detect and recognize traffic lights and traffic signs under heavy rainy weather conditions. The objective is to create a robust system that can accurately identify and classify traffic signals even in challenging visibility scenarios.

## Workflow

### 1. Data Acquisition

- **Navigation:** Drive a vehicle near traffic lights and traffic signs in various rainy weather conditions.
- **Image Capture:** Use an RGB camera to collect diverse images of traffic lights and signs.

### 2. Data Collection

- **Save Images:** Capture and save images of traffic lights and signs on the system for further processing.

### 3. Data Annotation

- **Annotation Tool:** Use the [Roboflow toolbox](https://roboflow.com/) to annotate the images.
- **Annotation Details:**
  - Draw bounding boxes around traffic lights and signs.
  - Label each object with its class.

### 4. Model Training

- **Model Used:** YOLOv8 (You Only Look Once version 8) for object detection.
- **Library:** `ultralytics` library for YOLOv8.
- **Platform:** Kaggle for training and computing resources.

### 5. Model Evaluation

- **Metric:** Evaluate the model's performance based on mean Average Precision (mAP).
- **Objective:** Assess the accuracy of the model in detecting traffic lights and signs.

## Getting Started
