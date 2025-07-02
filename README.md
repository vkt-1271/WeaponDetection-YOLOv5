# 🔫 WeaponDetection – YOLOv5-Based Object Detection System

**WeaponDetection-YOLOv5** is a computer vision project that uses the **YOLOv5** deep learning model to detect handheld weapons (e.g., guns and knives) in images or video streams. The goal is to provide a real-time safety surveillance solution by identifying threats using state-of-the-art object detection techniques.

## 📌 Project Overview

- Trained a **YOLOv5** model on custom-labeled data containing weapons and hand-held objects  
- Performs **real-time detection** of weapons in video feeds or camera input  
- Helps automate surveillance systems by detecting potential threats early  
- Includes pre-processing, model training, evaluation, and live inference pipeline

## 🧠 Key Features

- Detects **guns**, **knives**, and other handheld objects  
- Supports **image**, **video**, and **real-time webcam** inputs  
- Displays bounding boxes and labels with confidence scores  
- Custom-trained using **YOLOv5** for high accuracy and speed  
- Can be integrated into security or alert systems

## 🚀 Technologies Used

- **YOLOv5** – Real-time object detection (PyTorch implementation)  
- **Python** – Core programming language  
- **OpenCV** – Image and video processing  
- **LabelImg** or **Roboflow** – Dataset annotation and augmentation  
- **PyTorch** – Deep learning framework for model training and inference  

## 🧪 Example Output

- Detected weapon bounding boxes in red with confidence score
- Logs detection in the console
- Saves output images or video with annotations

## 💡 Use Cases

- Smart surveillance systems
- Public safety monitoring in stations, malls, etc.
- Automated alert systems in restricted zones
- Visual analytics in law enforcement applications
