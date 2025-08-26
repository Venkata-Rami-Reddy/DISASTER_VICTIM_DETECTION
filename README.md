# 🛠️ Disaster Victim Detection in Debris Environments

A deep learning–powered system for real-time human victim detection in disaster zones using RGB, thermal, and LiDAR imaging. Designed to assist Search and Rescue (SAR) teams by automating identification of body parts under debris with high accuracy and speed.

## 📌 Overview

This project proposes a hybrid AI model combining **ResNet-50**, **J48 Decision Tree**, and **XGBoost** to detect disaster victims (hand, leg, body) from complex debris environments. It leverages transfer learning and multi-modal sensor fusion to enhance detection in low-visibility conditions.

## 🚀 Features

- Custom dataset with labeled victim parts: `hand`, `leg`, `body`
- Transfer learning with **ResNet-50** for feature extraction
- Feature selection via **J48 Decision Tree Pruning**
- Classification using **XGBoost**, achieving 99.53% accuracy in 0.01s
- Real-time deployment on edge devices (drones, robots)
- Explainable AI integration: **Grad-CAM** and **SHAP**
- RGB + Thermal + LiDAR sensor fusion

## 🧰 Tech Stack

| Component        | Technology Used         |
|------------------|--------------------------|
| Deep Learning    | ResNet-50, VGG16         |
| ML Classifiers   | XGBoost, SVM, MLP, RF    |
| Preprocessing    | ImageDataGenerator, LabelEncoder |
| Visualization    | Grad-CAM, SHAP           |
| Deployment       | Edge devices, drones     |

## 📦 Installation

```bash
git clone https://github.com/Venkata-Rami-Reddy/disaster-victim-detection.git
cd disaster-victim-detection
pip install -r requirements.txt
