# 📹 VideoBroadcaster: Real-Time Webcam Streaming with Effects for Zoom, Google Meet, and More

VideoBroadcaster is a Python-based application that allows you to stream your webcam with visual effects (like background blurring, background replacement, and object detection) into video conferencing platforms such as **Zoom**, **Google Meet**, **Microsoft Teams**, etc. It uses powerful tools like **YOLOv8**, **OpenCV**, and **FastAPI**, and streams video via **OBS Virtual Camera** or similar methods.

---

## 🚀 Features

- ✅ Real-time webcam streaming
- ✅ Background blur or custom background replacement
- ✅ Person detection using YOLOv8
- ✅ Stream your processed video to any video conferencing tool (via OBS Virtual Cam or similar)
- ✅ Simple REST API to control video effects

---

## 🛠️ Tech Stack

- [FastAPI](https://fastapi.tiangolo.com/) — for building a lightweight web server and control panel
- [Uvicorn](https://www.uvicorn.org/) — ASGI server for FastAPI
- [OpenCV](https://opencv.org/) — for image processing
- [YOLOv8](https://github.com/ultralytics/ultralytics) — for real-time object/person detection
- [OBS Studio + Virtual Cam](https://obsproject.com/) — for streaming output to conferencing platforms

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YajatMakhija/videobroadcaster
cd videobroadcaster
