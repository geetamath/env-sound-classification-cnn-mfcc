# Environmental Sound Classification using CNN & MFCC

## 📌 Overview
This project focuses on classifying environmental sounds using deep learning techniques.
It uses MFCC features and CNN models to classify 10 different sound categories.

## 🎯 Features
- Classifies 10 environmental sounds (rain, thunder, fire, etc.)
- Uses MFCC feature extraction for improved accuracy
- Built using TensorFlow and Keras
- Interactive testing using Gradio UI

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- Librosa
- NumPy
- Gradio

## ⚙️ Workflow
1. Load audio dataset
2. Preprocess (normalize, trim)
3. Extract MFCC features
4. Train CNN model
5. Evaluate accuracy
6. Test using Gradio interface

## 📊 Results
- 1D CNN Accuracy: ~30%
- 2D CNN (MFCC): ~50%

## ▶️ Run the Project
```bash
pip install -r requirements.txt
python app.py
```

## 📁 Suggested Structure
```
project/
│── data/
│── models/
│── app.py
│── train.py
│── requirements.txt
│── README.md
```
