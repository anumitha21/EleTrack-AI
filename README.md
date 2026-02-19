# 🐘 EleTrack AI -- Elephant Detection & Warning System

## 📌 Project Overview

**EleTrack AI** is a real-time elephant detection and warning system
that uses **YOLOv5 and edge AI** to prevent elephant--train collisions.
The system analyzes live video streams from edge devices to accurately
detect elephants near railway tracks. When an elephant is detected, it
automatically triggers sound alerts to scare the animals away. This
project demonstrates the use of deep learning, computer vision, and IoT
for smart wildlife conservation and railway safety applications.

------------------------------------------------------------------------

## 🎯 Objectives

-   Detect elephants in real-time using deep learning\
-   Prevent elephant--train collisions\
-   Trigger sound alerts to repel elephants from railway tracks\
-   Deploy AI models on edge devices Jetson Orin Nano 
-   Support wildlife conservation using AI

------------------------------------------------------------------------

## 🧠 Technologies Used

-   **Deep Learning:** YOLOv5\
-   **Programming Language:** Python\
-   **Libraries & Frameworks:** PyTorch, OpenCV, NumPy, Ultralytics\
-   **Hardware:** NVIDIA Jetson Orin Nano, Raspberry Pi, Camera,
    Speaker/Buzzer

------------------------------------------------------------------------

## 📂 Dataset

Dataset: Elephants_19 (Roboflow)

Classes:

    0 - Elephant

Folder Structure:

    dataset/
    ├── train/images
    ├── train/labels
    ├── test/images
    ├── test/labels
    └── data.yaml

------------------------------------------------------------------------

## ⚙️ Model Training

### Install Dependencies

``` bash
pip install torch torchvision opencv-python ultralytics
```

## 🔊 Sound Alert Mechanism

When an elephant is detected, the system triggers a speaker or buzzer to
play warning sounds.


## 🌍 Impact

-   Prevents elephant deaths on railway tracks\
-   Reduces human--wildlife conflict\
-   Supports smart wildlife conservation\
-   Scalable for detecting other animals

------------------------------------------------------------------------

## 🚀 Future Enhancements

-   Thermal camera for night detection\
-   IoT-based SMS alerts\
-   Automatic train speed control\
-   Drone-based monitoring
