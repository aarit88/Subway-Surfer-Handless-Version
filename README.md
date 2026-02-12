# Subway-Surfer-Handless-Version
# 🎮 Subway Surfer – AI Handless Controller

Control Subway Surfers using your body movements!

This project uses **Computer Vision and MediaPipe Pose Detection** to detect body movement via webcam and convert it into keyboard arrow key presses.

No hands required. Just move your body to play.

---

## 🚀 Features

- Real-time pose detection using MediaPipe
- Controls Subway Surfers using body movement
- Works with browser-based Subway Surfers
- Uses OpenCV for webcam feed
- Uses pynput for keyboard automation

---

## 🧠 How It Works

The program:

1. Captures live webcam feed.
2. Detects shoulder midpoint using MediaPipe.
3. Determines movement direction (Left / Right / Up / Down).
4. Simulates arrow key press.
5. Controls the game in real time.

---

## 🛠️ Tech Stack

- Python 3.10
- OpenCV
- MediaPipe
- pynput

---

## 📦 Installation

### 1️⃣ Install Python 3.10

Download from:
https://www.python.org/downloads/release/python-31011/

### 2️⃣ Install Required Libraries

```bash
pip install opencv-python mediapipe==0.10.9 pynput
