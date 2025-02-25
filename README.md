# 🚀 YOLOv3: From Scratch to Precision Mastery

Dive into the heart of object detection with a fully implemented **YOLOv3 (You Only Look Once, Version 3)** model, meticulously built from scratch in PyTorch!

## 🔍 What’s Inside?
- **Pure Python Implementation:** Every line of code handcrafted for clarity and efficiency, from architecture to training.
- **PASCAL VOC & MS COCO Support:** Train and evaluate on two of the most popular datasets in the computer vision domain.
- **Augmentation Powerhouse:** Advanced image augmentations like Mosaic and CutMix to make your models robust to real-world challenges.
- **Anchor Management:** Adaptive anchor boxes for multi-scale object detection precision.
- **Modular Design:** Clean, reusable modules for the model, dataset, training, and utilities.
- **Performance-Driven:** Optimized with mixed-precision training and evaluation metrics like mAP.

## 🌟 Key Features
- **YOLOv3 Architecture:** From Darknet-53 backbone to multi-scale predictions.
- **Custom Loss Function:** A balanced mix of classification, objectness, and bounding box regression loss.
- **Real-Time Object Detection:** Detection at multiple scales with Non-Maximum Suppression (NMS).
- **Trainable on Any Dataset:** Plug in your custom dataset with minimal configuration tweaks.

## 🔧 How to Get Started
1. Clone the repo:
   ```bash
   git clone https://github.com/AndreiPopa1906/Yolov3.git
   cd Yolov3
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up your dataset paths and configurations in `config.py`.
4. Start training:
   ```bash
   python train.py
   ```
