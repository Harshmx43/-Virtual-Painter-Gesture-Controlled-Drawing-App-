# 🖐️ Gesture-Controlled Drawing App + 🧠 Life Predictor 3000

This repository contains two fun and interactive Python mini-projects:

---

## 🎨 1. Virtual Painter (Gesture-Controlled Drawing App)

A real-time drawing app that uses **hand gesture recognition** via your webcam to draw, undo, clear, and select colors using only your fingers!

### 🔧 Features
- Hand tracking using **MediaPipe**
- Draw on canvas using index finger
- Use multiple fingers for **undo**, **clear**, and **color selection**
- Save artwork as `.png` by pressing `s`

### 📁 Files
- `main.py`: The main script for running the virtual painter
- `HandTrackingModule.py`: Contains the reusable HandDetector class built with MediaPipe and OpenCV

### ▶️ How to Run
Install dependencies:
   ```bash
   pip install opencv-python mediapipe numpy
