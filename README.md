# Foot Ulcer Detection and Instance Segmentation using YOLOv8 & YOLOv11

A computer vision project that performs object detection and instance segmentation on diabetic foot ulcer images using YOLOv8 and YOLOv11.

## 🔍 Project Overview
This project aims to assist in early diagnosis of diabetic foot ulcers by detecting and segmenting ulcer regions in medical images using deep learning.

## 🛠️ Tech Stack
- Python
- YOLOv8 / YOLOv11 (Ultralytics)
- OpenCV
- PyTorch
- LabelImg (for annotation)

## 📁 Project Structure
- `data/` – Contains training images and labels
- `models/` – YOLOv8 and YOLOv11 trained models
- `notebooks/` – Jupyter notebooks for analysis
- `train.py` – Script to train models
- `inference.py` – Run model on new images
- `results/` – Inference outputs and evaluation metrics




## 🚀 Getting Started
```bash
git clone https://github.com/sourav2601/Instance-Segmentation-of-Foot-Ulcer.git
cd Instance-Segmentation-of-Foot-Ulcer
pip install -r requirements.txt
python inference.py --source sample.jpg --weights yolov8.pt

