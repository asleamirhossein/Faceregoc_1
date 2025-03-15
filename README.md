

Face Detection with Deep Learning

This project implements face detection using a deep learning model based on CNNs (Convolutional Neural Networks). The model is trained to detect faces in images and videos with high accuracy.

Project Overview

 • Utilized Deep Learning-based face detection techniques.
 • Trained on a large-scale face dataset for robust performance.
 • Implemented using PyTorch and OpenCV.
 • Supports both image and real-time webcam detection.

Dataset

The model was trained on a face dataset containing various facial images with different:

 • Lighting conditions
 • Angles
 • Expressions
 • Backgrounds

Installation

To run this project, install the required dependencies:

pip install torch torchvision opencv-python numpy matplotlib

Usage

For Image Face Detection:

Run the following command:

python detect_faces.py --image path/to/image.jpg

For Real-Time Webcam Face Detection:

python detect_faces.py --webcam
