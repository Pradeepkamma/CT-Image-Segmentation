# 🧠 CT-Image-Segmentation

## 📌 Overview
This project focuses on segmenting lung infection regions from CT scan images using Deep Learning techniques.

## 🎯 Objectives
- Accurate segmentation of COVID-19 infected regions
- Improve diagnostic support systems
- Use Dense Context Learning for better feature extraction

## 🏗️ Architecture
- Encoder-Decoder (UNet based)
- Transformer + HarDNet modules
- Feature Fusion Module

## 📊 Diagrams
### Use Case
![Use Case](diagrams/use-case-diagram.png)

### Activity Diagram
![Activity](diagrams/activity-diagram-dice.png)

### Sequence Diagram
![Sequence](diagrams/sequence-diagram.png)

## 📈 Metrics
- Dice Coefficient
- IoU
- Accuracy
- Precision
- Recall
- F1 Score

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- OpenCV

## 🚀 How to Run
```bash
pip install -r requirements.txt
python train.py
