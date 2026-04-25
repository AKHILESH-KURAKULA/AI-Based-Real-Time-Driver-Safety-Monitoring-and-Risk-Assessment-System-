# AI-Based-Real-Time-Driver-Safety-Monitoring-and-Risk-Assessment-System-

### 📌 Problem Statement

Road accidents caused by driver fatigue, distraction, and unsafe behaviors are a major concern worldwide. Many existing safety systems either rely on expensive hardware or fail to provide real-time monitoring of driver actions such as drowsiness, yawning, mobile phone usage, and inattentiveness. This creates a need for an affordable, accurate, and real-time driver monitoring system that can continuously analyze driver behavior and alert them before a potential accident occurs. The challenge lies in integrating multiple detection techniques efficiently while ensuring the system remains lightweight, scalable, and suitable for deployment on standard consumer devices without requiring specialized equipment.

### 💡 Solution

This project presents an AI-powered Driver Monitoring System that leverages computer vision and deep learning techniques to detect unsafe driver behaviors in real time. Using a standard webcam, the system integrates facial landmark detection through MediaPipe to monitor eye closure, yawning, and head pose, while YOLO-based object detection identifies distractions such as mobile phone usage. The system processes video frames continuously, classifies driver states into categories like normal, drowsy, distracted, and phone usage, and triggers alerts when risky behavior is detected. Additionally, it logs driver activity data for further analysis and visualization using graphs, enabling performance evaluation and scoring. Designed with a modular architecture, the system is cost-effective, easy to extend, and capable of running on CPU-based systems, making it practical for real-world applications and scalable improvements.
