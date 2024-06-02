Project Description:
The project involves building a real-time object detection system using YOLO (You Only Look Once) algorithm with a webcam feed. YOLO processes the entire image in a single pass, making it faster and more efficient than traditional object detection algorithms. The system captures frames from the webcam, detects objects in the frames using YOLO, and displays the frames with bounding boxes around the detected objects and labels indicating the class of each object.

Modules and Libraries Used:
OpenCV (cv2):

Used for capturing frames from the webcam and displaying images.
Provides functions for drawing bounding boxes and text on images.
Ultralytics:

A library used to work with YOLO models in Python.
It simplifies the process of loading and uses YOLO models for object detection.
Math:

Used for mathematical operations, such as rounding confidence scores.

YOLO Model Weights (yolov8n.pt):

Pre-trained YOLO model weights used for object detection.
The ultralytics library loads and utilizes this model for real-time detection.
Class Names List:

Contains a list of object classes that the YOLO model is trained to detect.
Used for mapping class indices to human-readable class names.
Main Script (main.py):

Contains the main code for capturing webcam frames, performing object detection using YOLO, and displaying the results.
Utilizes the OpenCV and Ultralytics libraries.
