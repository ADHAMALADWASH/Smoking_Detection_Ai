# 🚭 Real-Time Smoking Detection System using YOLOv8

A real-time AI system for smoking and cigarette detection using a webcam. Built with YOLOv8 for computer vision, OpenCV for video processing, and PyTorch with CUDA for GPU acceleration. The system features instant audio alarms and visual on-screen alerts when smoking is detected, making it ideal for smart surveillance and automated safety monitoring.

---

## ✨ Features
- **⚡ Real-Time Analysis:** Fast video stream processing using OpenCV.
- **👀 Visual Alerts:** Displays the current environment status on-screen:
  - `STATUS: SAFE` (Green text) when no cigarette is detected.
  - `STATUS: SMOKING DETECTED!` (Red text) with a precise bounding box around the detected cigarette.
- **🔊 Audio Alarm:** Automatically triggers a high-frequency beep sound using Windows' native `winsound` to alert personnel.
- **🚀 GPU Acceleration:** Fully compatible with NVIDIA GPUs via CUDA 11.8 for high-speed, lag-free inference (Tested on RTX 3050 Laptop GPU).

---

## 🛠️ Tech Stack
- **Language:** Python 3.11
- **AI/Computer Vision:** YOLOv8 (Ultralytics), OpenCV (`cv2`)
- **Deep Learning Framework:** PyTorch
- **Audio Notification:** `winsound` (Windows built-in)

---
