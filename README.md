# 🕵️‍♂️ Muraqib - AI SCAI League Project

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

## 🗃️ Dataset

The dataset used for this project is the **Violence Detection Dataset**, available on Kaggle. It contains images and videos labeled for violence detection in various settings, which are ideal for training and testing the model to detect violence and abnormal actions in stadiums. 🎥📸

### Dataset Details:
- **Source:** [Violence Detection Dataset on Kaggle](https://www.kaggle.com/datasets/engmohamedsshubber/violencedetectiondataset) 🌐
- **Format:** Video files (MP4), Image files (JPEG) 🎞️
- **Size:** 1.1 GB 📊
- **Features:**
  - **Violence detection:** Contains labeled instances of violent behavior, including various types of violent actions. 💥

### Preprocessing:
- Videos are processed frame by frame. 🎬
- Images are resized and normalized for model input. 📏
- Annotations include labeled instances of violence and normal fan behavior. 🏷️

### How to Access:
You can download the dataset from [Violence Detection Dataset on Kaggle](https://www.kaggle.com/datasets/engmohamedsshubber/violencedetectiondataset). Make sure to follow the appropriate steps for accessing and using the dataset according to Kaggle's terms and conditions. 📥


## 🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/iimustafa/muraqib-ai.git
   cd muraqib-ai
