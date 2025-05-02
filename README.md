# 🚗 Automatic Number Plate Recognition (ANPR) 📷

[![Status](https://img.shields.io/badge/status-completed-brightgreen.svg)]()
[![Python](https://img.shields.io/badge/python-3.8+-blue.svg)]()

Welcome to my **Automatic Number Plate Recognition (ANPR)** project!  
This project showcases my work in developing and evaluating deep learning and machine learning methods for recognizing vehicle license plates under real-world conditions.

✅ **Developed by Adit Ghanshyam Patel at Arizona State University**

> _This project was completed as part of a team coursework project, with contributions from peers._

---

## 📚 Table of Contents
- [Introduction](#introduction)
- [Key Features](#key-features)
- [Dataset](#dataset)
- [Methods](#methods)
- [Results](#results)
- [Future Directions](#future-directions)
- [Read the Full Report](#read-the-full-report)

---

## 📝 Introduction
Automatic Number Plate Recognition (ANPR) plays a pivotal role in law enforcement, traffic management, and smart cities.  
This project evaluates several models, including **ResNet50, AlexNet, InceptionV3, MobileNetV2, VGG16, and Random Forest**, for their ability to accurately identify license plates in challenging environments.

---

## 🚀 Key Features
✅ License plate recognition using multiple deep learning architectures  
✅ Data augmentation and preprocessing for real-world robustness  
✅ Performance comparison across models using **accuracy, recall, F1-score**  
✅ Achieved 94.29% accuracy with InceptionV3  
✅ Completed as part of **CS coursework at Arizona State University**

---

## 🗂️ Dataset
- Sourced from [Kaggle](https://www.kaggle.com/datasets/gpiosenka/us-license-plates-image-classification/data)
- Contains **8,000+ images** of US license plates under various conditions
- Includes training, validation, and test splits
- Preprocessing: resizing, normalization, augmentation

---

## 🧠 Methods
Models explored in this project:

| Model        | Accuracy (%) |
|--------------|--------------|
| ResNet50      | 85.24        |
| AlexNet       | 55.45        |
| InceptionV3   | 94.29        |
| MobileNetV2   | 70.47        |
| VGG16         | 40.25        |
| Random Forest | 63.47        |

> 🔍 **InceptionV3 achieved the highest accuracy of 94.29%!**

We used a combination of CNN-based models and Random Forest to benchmark traditional and deep learning approaches.

---

## 📈 Results
| Metric      | ResNet50 | AlexNet | InceptionV3 | MobileNetV2 | VGG16 | Random Forest |
|-------------|----------|---------|-------------|-------------|-------|---------------|
| Accuracy (%) | 85.24    | 55.45   | 94.29       | 70.47       | 40.25 | 63.47         |
| F1-score (%) | 83.5     | 50.2    | 92.3        | 68.1        | 37.6  | 60.5          |
| Recall (%)   | 84.2     | 52.8    | 94.1        | 70.9        | 38.9  | 62.2          |

✅ Deep learning models significantly outperformed traditional machine learning approaches.

---

## 🎯 Future Directions
✅ Optimize models for real-time inference  
✅ Explore hybrid methods combining deep learning and rule-based approaches  
✅ Evaluate models under diverse environmental conditions  
✅ Implement attention mechanisms for finer recognition

---

## 📥 Read the Full Report
Want to dive deeper into the project details?

👉 [**Click here to view the full PDF report**](./Automatic%20Number%20Plate%20Recognition.pdf)

Alternatively, download the report directly from this repository.
