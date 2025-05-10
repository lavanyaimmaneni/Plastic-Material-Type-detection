# Plastic Recyclable Detection with YOLOv8

## Overview
This repository contains a real-time plastic recyclable detection system using the YOLOv8 model, deployed with a USB webcam on a CPU-based system.

## Setup
1. Create a virtual environment: `python -m venv yolo_env`
2. Activate it: `yolo_env\Scripts\activate` (Windows)
3. Install dependencies: `pip install ultralytics opencv-python numpy`
4. Update `model_path` and `output_dir` in `predict.py` to match your local paths.

## Usage
Run `python predict.py` to start webcam prediction with updated class names.

## Files
- `predict.py`: Main script for webcam inference.
- `plastic_detection_results/weights/`: Contains `best.pt` and `last.pt`.
- `video_inference_results/`: Directory for saved annotated frames (generated during runtime).