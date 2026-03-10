# 🐟 Fish Detection using YOLOv8 (Edge AI)

A professional computer vision web application for detecting fish species from images using YOLOv8.

## 🔍 Features
- Fish detection & classification (26 classes)
- Scientific → common name normalization
- Image-only inference
- Clean dark-mode web UI
- Side-by-side original & detected image view
- Edge-device ready architecture

## 🧠 Tech Stack
- YOLOv8 (Ultralytics)
- FastAPI
- OpenCV
- Python 3.10
- HTML + CSS (Dark UI)

## 🚀 How to Run

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
uvicorn app:app 

