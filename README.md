# 🚦 Helmet Detection System using Improved YOLOv5s

This project presents a deep learning-based system for real-time helmet violation detection using an enhanced version of YOLOv5s. The system is designed to monitor motorcycle riders and passengers for helmet usage in varying real-world conditions.

## 📌 Project Highlights

- **Objective**: Detect and classify motorcycle riders and passengers based on helmet usage using real-time video footage.
- **Model**: Improved YOLOv5s with SE attention and ShuffleNetV2 integration.
- **Framework**: PyTorch and YOLOv5
- **Ensemble Learning**: Combines 5 models with different hyperparameters for robust performance.
- **Dataset**: 100 real-world 1920×1080 videos recorded in India, with diverse lighting and weather conditions.

## 🧠 Features

- Real-time helmet violation detection
- Handles varied traffic, lighting, weather, and camera angles
- Utilizes data augmentation: flipping, rotation, blur, mosaic
- Uses COCO-pretrained models fine-tuned on custom dataset

## 🧪 Results

| Model          | mAP (mean Average Precision) |
|----------------|------------------------------|
| YOLOv5 Ensemble| **0.5267**                   |
| Ranking        | 11th place in AI City Challenge 2023 |

## 🏗️ Model Architecture

- **YOLOv5s (Improved)**: Integrated SE module, enhanced feature pyramid, optimized loss functions
- **Other Models Used**: YOLO9000, RetinaNet, Inception V3, KNN
- **Techniques**: Anchor box tuning, attention mechanism, AutoML for hyperparameter optimization

## 📊 Dataset Labels

1. Motorcycle  
2. Driver with helmet  
3. Driver without helmet  
4. Passenger with helmet  
5. Passenger without helmet  

## 🔧 Tools & Technologies

- YOLOv5 (PyTorch)
- OpenCV
- CVAT for annotation
- COCO & custom datasets

## 📁 Files

- `NNDL Article.pdf` – Project documentation
- `model_weights/` – Saved model weights
- `inference/` – Test scripts and results
- `notebooks/` – Training & evaluation notebooks

## 📈 Future Work

- Expand training dataset across different countries
- Improve mAP through better augmentation and real-time optimizations
- Integrate with smart city infrastructure for live traffic law enforcement

## 📝 References

Includes academic and practical sources related to YOLO, helmet detection, and deep learning. (Full list in the PDF article)
