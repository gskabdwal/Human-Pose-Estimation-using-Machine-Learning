# Human Pose Estimation using Machine Learning

## Problem Statement

Human pose estimation involves detecting and tracking key body joints (e.g., shoulders, elbows, knees) in images or videos. Despite advancements in computer vision, challenges persist in achieving real-time processing, handling occlusions, and maintaining accuracy across diverse poses, lighting conditions, and body types. Traditional methods often struggle with computational efficiency or fail under dynamic environments. This problem is significant because accurate pose estimation is foundational to applications like healthcare (physical therapy), sports analytics, surveillance, and human-computer interaction. Addressing these limitations can unlock scalable, real-world solutions for motion analysis and behavioral understanding.

## Motivation

This project was chosen due to the growing demand for automated systems capable of interpreting human motion in real time. Applications include:
•	Healthcare: Monitoring patient rehabilitation exercises.
•	Fitness: Analyzing workout form and preventing injuries.
•	Entertainment: Enhancing AR/VR experiences and gesture-controlled interfaces.
•	Surveillance: Detecting abnormal behaviors in public spaces.
The impact lies in bridging the gap between theoretical pose estimation research and deployable solutions, enabling cost-effective, accessible tools for diverse industries. Advances in machine learning (ML) and frameworks like MediaPipe/OpenPose further motivated this work, as they democratize complex computer vision tasks.

## Objective

The primary objectives of this project are:
1.	To design and implement a machine learning-based system for 2D human pose estimation using tools like OpenCV and Streamlit.
2.	To achieve real-time performance on moderate hardware while maintaining accuracy.
3.	To create an intuitive user interface for visualizing pose keypoints on images/videos.
4.	To evaluate the system’s robustness under varying conditions (lighting, occlusions, pose complexity).

## Scope of the Project

o	2D pose estimation using pre-trained ML models (e.g., MediaPipe).
o	Support for static images and real-time video input.
o	Basic visualization of keypoints and skeletal connections.
o	Performance benchmarking on standard datasets.
•	Limitations:
o	Focus on 2D poses (no 3D depth estimation).
o	Accuracy drops under heavy occlusion or extreme poses.
o	Hardware-dependent processing speed (not optimized for low-end devices).
o	Limited to single-person pose estimation.


## Technologies Used:
- Streamlit
- OpenCV
- Numpy
- Matplotlib
- Pillow
