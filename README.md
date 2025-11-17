🧠 AI Smart Surveillance

An intelligent, real-time surveillance system powered by computer vision and machine learning.
This project detects people, vehicles, and unusual activity in live video feeds using advanced deep-learning models.

📌 Overview

AI Smart Surveillance is designed to enhance traditional CCTV systems by making them automated, accurate and smart.
Instead of passively recording, this system:

Detects objects (people, cars, bikes, etc.)

Tracks movements

Triggers alerts for suspicious activities

Saves snapshots/clips

Works with webcam, CCTV camera (RTSP), or video files

You can use it for home surveillance, shop security, parking monitoring, and smart-city applications.

✨ Features

🎯 Real-time object detection (YOLO, MobileNet, or custom models)

🚶 Person & vehicle tracking using SORT/DeepSORT

🚨 Alert system (email/SMS/desktop alerts)

🎥 Supports multiple input sources:

Webcam

CCTV IP camera (RTSP)

Local video files

💾 Auto-save snapshots and event logs

🧩 Modular code — plug in your own models or logic

🔋 GPU support for faster inference (optional)

⚡ Lightweight enough for edge devices (Raspberry Pi)

🏗️ System Architecture

          ┌──────────────────────────────┐
          │          Input Source        │
          │ Webcam / Video / RTSP Stream │
          └───────────────┬──────────────┘
                          ↓
               ┌────────────────────────┐
               │     Pre-processing     │
               └───────────────┬────────┘
                              ↓
                   ┌──────────────────┐
                   │  Object Detector │  ← YOLO / SSD
                   └───────┬──────────┘
                           ↓
                  ┌────────────────────┐
                  │ Tracking & Rules   │ ← SORT / DeepSORT
                  └────────┬───────────┘
                           ↓
           ┌──────────────────────────────────────┐
           │ Alerts │ Saving │ Logging │ Monitoring│
           └──────────────────────────────────────┘






