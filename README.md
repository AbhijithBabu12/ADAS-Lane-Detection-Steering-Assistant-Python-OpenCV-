# ADAS-Lane-Detection-Steering-Assistant-Python-OpenCV-
Built a real-time lane detection and driver assistance system using edge detection + Hough Transform

🚗 Lane Detection with ADAS Features

📌 Overview

This project implements a Lane Detection System enhanced with ADAS (Advanced Driver Assistance System) features using OpenCV and Python.
It mimics functionalities seen in modern driver assistance systems like Tesla Autopilot and includes:

✅ Lane detection with smooth left & right green lanes
✅ Lane area filling (shaded region between lanes)
✅ Steering angle computation from lane midpoint
✅ Blue arrow showing steering direction
✅ Curvature radius estimation using polynomial fitting
✅ Lane departure warning system


⚡ Features

Lane Detection: Uses Canny Edge + Hough Transform to extract lane lines.

Lane Smoothing: Averages slopes and intercepts for stable lane tracking.

Lane Fill: Shades the drivable lane area (like Tesla Autopilot).

Steering Angle: Dynamically computed from lane midpoint.

ADAS Overlay: Blue steering arrow, curvature radius, lane departure alerts.

Realtime Processing: Works on driving videos or webcam streams.

🛠️ Tech Stack

Language: Python 3.8+

Libraries:

OpenCV (Computer Vision)

NumPy (Matrix & Math Ops)

Math (Trigonometry for steering angle)


🚀 Getting Started
🔹 Clone the repo
git clone https://github.com/yourusername/lane-detection-adas.git
cd lane-detection-adas

🔹 Install dependencies
pip install opencv-python numpy

📂 Project Structure
📦 lane-detection-adas
 ┣ 📜 lane_detection_full.py   # Main script
 ┣ 📜 test_video.mp4           # Sample test video (add your own)
 ┣ 📜 README.md                # Project documentation
 ┗ 📜 requirements.txt         # Dependencies

 📊 Output Example

Green lanes overlaid on the road
Lane area shaded
Steering direction (blue arrow)
Curvature radius text (px)
Lane departure warning ⚠
