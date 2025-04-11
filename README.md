# 🚗 Live Car Detection

This project implements **real-time car detection** using computer vision techniques and OpenCV. It leverages pre-trained Haar cascade or deep learning models to identify vehicles in live video streams, whether from a webcam or a traffic surveillance video.

---

## 🎯 Project Goals

- Detect moving cars in real-time from live video or webcam feed
- Draw bounding boxes around detected vehicles
- Enable easy switch between pre-trained detection models
- Lightweight and easy to deploy on any machine with Python + OpenCV

---

## 🧠 Features

- ✅ Real-time vehicle detection using:
  - Haar Cascades
  - DNN-based detectors (optional)
- ✅ Input options:
  - Live webcam stream
  - Pre-recorded traffic video file
- ✅ Bounding boxes with labels on detected cars
- ✅ Simple, modular code structure

---

## 📁 Project Structure

```bash
live-car-detection/
├── car_detection_haar.py
├── video_input.mp4  # (optional input video)
├── models/
│   └── cars.xml     # Haar cascade model
├── requirements.txt
└── README.md


⚙️ Setup Instructions
1. Clone the Repository:
git clone https://github.com/siddarthx07/live-car-detection.git
cd live-car-detection

2. Create a Virtual Environment (optional)
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt
Or manually:
pip install opencv-python numpy
🚀 Run the Project
▶️ Detect Cars from Webcam
python car_detection_haar.py
▶️ Detect Cars from a Video File
python car_detection_haar.py --video video_input.mp4


📸 Sample Output
<table> <tr> <td><img src="docs/sample_car_1.png" width="300"/></td> <td><img src="docs/sample_car_2.png" width="300"/></td> </tr> </table>
🛠️ Tools & Libraries
Python

OpenCV

Haar Cascades (cars.xml)
