# Vehicle-Movement-Detection-and-Counting-in-Video

# Project Overview
This project demonstrates vehicle detection, tracking, and movement analysis in video footage. Using the YOLOv5 model for object detection, the SORT (Simple Online and Realtime Tracking) algorithm for tracking, and custom logic for vehicle movement analysis, this project provides a complete pipeline for identifying vehicles, tracking their movements, and displaying relevant information on the video.

# Key Features
#Vehicle Detection: Utilizes YOLOv5 for real-time vehicle detection.
#Vehicle Tracking: Implements SORT algorithm for tracking vehicles across video frames.

# Movement Analysis 

Determines whether vehicles are moving or stagnant based on displacement between frames.
Counting and Annotation: Displays the count of different vehicle types and their movement status on the video frame.

# Output Video: 

Saves the processed video with annotations indicating vehicle status and counts.

Requirements

Python 3.x

PyTorch

OpenCV

NumPy

sort Python package (Simple Online and Realtime Tracking)
ultralytics YOLOv5 PyTorch Hub model
