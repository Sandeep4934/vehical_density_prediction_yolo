Project Overview:
This project implements an intelligent traffic analysis system using YOLOv8 to detect, classify, and analyze vehicles from top-view traffic videos.
The system not only estimates traffic density (smooth vs heavy) but also identifies vehicle types such as cars, trucks, and buses, along with lane-wise and total vehicle counts.
It is designed for real-time traffic monitoring, smart city applications, and traffic signal optimization.

System Architecture:

Input
Traffic images or video streams (top-view camera)

Preprocessing
Frame extraction from video
Region of Interest (ROI) masking

Detection & Classification
YOLOv8 model detects and classifies vehicles

Analysis
Lane-wise vehicle counting
Vehicle-type counting
Traffic density estimation

Output
Annotated video frames
Vehicle counts & density labels
