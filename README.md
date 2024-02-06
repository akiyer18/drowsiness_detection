# Drowsiness Detection using OpenCV and YOLOv5

This repository contains code for detecting drowsiness using OpenCV and YOLOv5.

## Overview

1. **Model Loading**: The YOLOv5 model is loaded using PyTorch.
2. **Object Detection**: The model is used to perform basic object detection on a sample image downloaded from the internet.
3. **Real-time Detection**: Real-time detection is captured using the webcam.
4. **Custom Dataset Preparation**: Pictures of drowsy or active faces are captured using the webcam, labeled, and used for training.
5. **Detection Based on Custom Dataset Training**: Drowsiness detection is performed based on the custom dataset training.

## Usage

1. Clone the repository:

git clone https://github.com/akstud/drowsiness_detection.git
cd drowsiness_detection


2. Install the required dependencies:

pip install -r requirement.txt


3. Run the main script:

python drowsiness_detection.ipynb


## Dependencies

- torch
- torchvision
- numpy
- opencv-python
- matplotlib

