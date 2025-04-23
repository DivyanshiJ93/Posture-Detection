# Posture-Detection


# 💪 PoseTracker: Arm Curl Counter using Mediapipe

This project uses **Mediapipe** and **OpenCV** to detect human poses in real-time and count arm curl repetitions. It is designed as a lightweight physiotherapy aid to assist with upper limb rehabilitation and fitness tracking.


## 🚀 Features

- 🎯 **Pose Detection** using Mediapipe’s Pose module  
- 🧠 **Angle Calculation** at the elbow to determine curl motion  
- 🔄 **Automatic Rep Counting** using angle thresholds and movement state tracking  
- 🖥️ **Real-Time Feedback** via OpenCV visualization  
- 📈 **Accuracy Optimized** for left/right hand curls and adaptable thresholding

## 🧰 Tech Stack

- Python 3
- Mediapipe
- OpenCV
- Numpy

## 📊 Logic Overview

1. Detect keypoints with Mediapipe (shoulder, elbow, wrist).
2. Calculate the angle at the elbow.
3. Track movement:  
   - Angle < 50° → "Curl"  
   - Angle > 150° → "Extend"
4. Count reps on successful "Curl → Extend" cycles.

## 🎯 Thresholds

- These can be fine-tuned based on user movement and flexibility.
- Supports left/right arm toggle via code update.


## 👩‍⚕️ Use Case

Originally developed as a part of **elderly physiotherapy support**, this project is now a standalone lightweight tool for basic upper-body rehab and exercise tracking. Can be adapted for gyms, home workouts, and physical therapy.

---

> Made with 💪 by [Divyanshi Jain](https://github.com/DivyanshiJ93)

