# YOLOv8 Segmentation – Object Masking Demo

This repository contains a simple Python demo using **YOLOv8 segmentation**
to mask only the exact object pixels (no bounding boxes) in a live webcam feed.

### What it shows
- Pixel-level object masking using YOLOv8 segmentation
- Only the object shape is masked, hand/background remains intact
- Real-time webcam inference

### Tech stack
- Python
- Ultralytics YOLOv8
- OpenCV
- NumPy

### How to run
```bash
pip install ultralytics opencv-python numpy
python yolo_seg_object_mask.py
