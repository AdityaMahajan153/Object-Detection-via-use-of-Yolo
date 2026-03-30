# 🎯 Object Detection using YOLOv8

## 📌 Overview
This project implements a real-time object detection system using YOLOv8. The model can detect multiple objects in images or videos and draw bounding boxes with labels and confidence scores.

---

## 🎯 Features
- Detects 80+ object classes (COCO dataset)
- Works with video input (uploaded file)
- Real-time frame-by-frame processing
- Outputs annotated video with bounding boxes
- No dependency on Google Drive

---

## 🛠️ Tech Stack
- Python
- OpenCV
- YOLOv8 (Ultralytics)
- Google Colab

---

## 📂 Workflow
1. Upload input video
2. Load YOLOv8 pretrained model
3. Process video frame-by-frame
4. Detect objects in each frame
5. Draw bounding boxes and labels
6. Save output video

---

## ▶️ How to Run

### Install dependencies
```bash
pip install ultralytics opencv-python
