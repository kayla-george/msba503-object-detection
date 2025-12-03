# MSBA 503 Take-Home Assignmnet: Object Detection

This repository contains the code for the MSBA take-home assignment on object detection. This notebook compares two deep learning models, YOLOv8m and Faster R-CNN (ResNet50-FPN), on a set of eleven images. For each image and model, the code records the number of detected objects, average prediction confidence, and inference time, and also extracts three simple image features, width, height, and average brightness. Images themselves are **not** included in this repository.

## How to Run the Notebook

1. Create and activate a conda environment (example):
   ```bash
   conda create -n yolo503 python=3.10
   conda activate yolo503
2. Install required packages:
   ```bash
   pip install ultralytics torch torchvison pillow numpy pandas jupyter
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
4. Open detection_script.ipynb and run all cells. 
