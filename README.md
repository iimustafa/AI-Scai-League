# 🕵️‍♂️ Muraqib - SCAI AI League Project

**Track:** Smart Stadiums and Fan Experience  
**Team:** Muraqib - مُراقب  
**Members:** Mustafa Al Ali, Yasmin Al Suliman, Yousif Al Nasser, Bader Al Fakhri
**Challenge:** SCAI AI League (2025)

## 📌 Overview
Muraqib is an AI-powered system designed to monitor stadium crowds to:
- Detect violent behavior or abnormal actions.

## ⚽ Use Case
This system is built for Saudi League stadiums, analyzing fan behavior from a top-down view using OpenCV.

## 🧠 Model
We use a **MobileNet + BiLSTM** architecture to:
- Extract visual features.
- Classify crowd behavior over time.

### 📊 Model Performance
- **Training Accuracy:** ~95%
- **Validation Accuracy:** ~90%
- **Loss Function:** Binary Crossentropy

## 🛠️ Tools & Tech
- Python, Keras, TensorFlow
- Matplotlib, OpenCV
- Custom anomaly detection pipeline

## 📂 Files
- `Muraqib_SCAI_AI_League.ipynb` – main notebook
- `README.md` – this file
- `requirements.txt` – for dependencies

## 🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/muraqib-ai.git
   cd muraqib-ai
