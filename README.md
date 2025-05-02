# AMBULANCE-DETECTION-SYSTEM
The ambulamce detection system detects the incoming ambulances in the diversion and helps clear traffic congestion to avoid delays in times emergency Ambulance Detection System for Traffic Signal Optimization
Project Overview This project implements an intelligent traffic signal optimization system that automatically detects emergency vehicles (specifically ambulances) using multiple computer vision techniques. When an ambulance is detected, the system can automatically adjust traffic signals to prioritize emergency vehicle passage. Features
Multi-Modal Detection System: Combines multiple detection methods for robust ambulance identification:

CNN-based vehicle classification YOLO object detection Emergency light pattern analysis Color and pattern recognition using OpenCV Text detection for "AMBULANCE" markings

Real-time Processing: Processes video feeds in real-time to detect emergency vehicles Traffic Signal Control: Automatically determines optimal signal states based on detection results User-friendly Interface: Implements a Gradio web interface for easy interaction and visualization
Technical Stack:-

Python 3.10+ PyTorch for deep learning YOLOv8 for object detection OpenCV for image processing Gradio for the web interface Additional libraries: NumPy, torchvision, supervision
Output The system provides:

Visual output with bounding boxes around detected ambulances Emergency light detection indicators Traffic signal state recommendations (RED/GREEN)
