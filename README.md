# Desert Lens – AI-Based Urban vs Desert Classification (Oman Vision 2040)

## Overview
Desert Lens is a deep learning-based system designed to classify satellite and drone imagery into **urban and desert regions**, supporting environmental monitoring, urban planning, and sustainable infrastructure development in Oman.

This project was presented at the **Cibirx AI Hackathon 2025 (MCBS)** and received strong recognition for its real-world application.

---

## Problem Statement
Rapid urbanization and land degradation require efficient monitoring of terrain changes. Traditional methods are slow and resource-intensive, making AI-based automated classification essential for real-time analysis.

---

## Solution Approach

### 1. Data Preprocessing
- Image rescaling and normalization (0–1 range)  
- Image resizing to 256x256  
- Train-validation split (80/20)  

---

### 2. Model Development
- Implemented **ResNet50 (pre-trained on ImageNet)** for feature extraction  
- Frozen base layers to retain learned features  
- Added custom dense layers with **Dropout for regularization**  

---

### 3. Training & Evaluation
- Trained model on labeled desert vs urban image dataset  
- Evaluated performance using:
  - Confusion Matrix  
  - Precision, Recall, F1-score  

---

## Key Features
- Automated classification of terrain (Urban vs Desert)  
- Supports environmental monitoring and land-use analysis  
- Scalable for integration with satellite and drone data  

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- Transfer Learning (ResNet50)  
- Image Data Processing  

---

## Impact
- Enables **data-driven urban planning and environmental monitoring**  
- Supports **Oman Vision 2040 sustainability goals**  
- Applicable to disaster management and climate analysis  

---

## Outcome
Successfully developed a deep learning-based terrain classification system demonstrating practical application of AI in **sustainability, infrastructure planning, and environmental analytics**.

---
