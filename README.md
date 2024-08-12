# Let's write the README content into a .md file and save it.
readme_content = """
# Autonomous Vehicle Obstacle Detection and Segmentation in South Asian Road Conditions

## Project Overview

This project aims to improve autonomous vehicle navigation by developing a fast and efficient object detection and segmentation system. The focus is on handling diverse and challenging road conditions prevalent in South Asian countries, with a particular emphasis on Bangladesh. We utilized YOLO-based models (YOLOv5, YOLOv7, and YOLOv8) to detect and segment various road obstacles such as potholes, speed bumps, and barricades.

## Dataset

- **Source**: Videos captured from roads in and around Dhaka, Bangladesh.
- **Annotations**: Images were annotated with bounding boxes and masks using Roboflow.
- **Classes**:
  - Barricade
  - Normal Road
  - Pothole
  - Speed Bump
- **Conditions**: Videos were recorded under various conditions including clear daylight, nighttime, rainy weather, and dusk.

## Models

Three different YOLO models were trained using the custom dataset:
- **YOLOv5**
- **YOLOv7**
- **YOLOv8**

### Model Performance
- **Best Model**: YOLOv5x
  - **mAP50**: 0.876
  - **mAP50-95**: 0.647
- **Lowest Performing Model**: YOLOv7x
  - **mAP50**: 0.583
  - **mAP50-95**: 0.331

## Implementation

- **Frameworks**: PyTorch, Roboflow
- **Deployment**: Models were deployed locally to enable real-time obstacle detection using a camera feed. The prototype system allows an autonomous vehicle to make decisions based on detected obstacles using a microprocessor.

## Key Features

- Custom dataset tailored for Bangladeshi road conditions.
- Real-time object detection with high accuracy using YOLOv5x.
- Deployment on local hardware for live obstacle detection.


