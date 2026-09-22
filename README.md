# Sound Event Detection using Machine Learning, Deep Learning and Hybrid Learning

## 📌 Project Overview

This project presents an AI-based Sound Event Detection system for identifying environmental, emergency, and potentially hazardous sounds. The system analyzes audio signals and provides a final classification as **Safe** or **Unsafe**.

The project investigates Machine Learning (ML), Deep Learning (DL), Transfer Learning, and Hybrid Learning approaches for sound classification.

## 🎯 Objective

The main objective of this project is to develop an intelligent sound detection system capable of identifying potentially hazardous or emergency-related sounds and producing a simple **Safe/Unsafe** output.

## 📂 Datasets

The project uses the following publicly available audio datasets:

- UrbanSound8K
- ESC-50
- FSD50K

## 🔧 Audio Preprocessing

The audio data is preprocessed using Python and Librosa:

- Audio loading from `.wav` files
- Resampling to 22.05 kHz
- Silence removal using `librosa.effects.trim()`
- Fixed 3-second audio duration
- Cropping longer audio
- Zero-padding shorter audio
- Audio normalization

## 🎵 Feature Extraction

The following audio features are extracted:

- MFCC (Mel-Frequency Cepstral Coefficients)
- MFCC Mean
- MFCC Standard Deviation
- Chroma STFT

## 🤖 Machine Learning Models

The following Machine Learning models were investigated:

- Support Vector Machine (SVM) — 94%
- Logistic Regression — 84%
- K-Nearest Neighbors (KNN) — 93%
- Random Forest — 88%

## 🧠 Deep Learning Models

The following Deep Learning models were investigated:

- Convolutional Neural Network (CNN) — 94%
- VGG16 — 96%
- LSTM — 85%

## 🔄 Transfer Learning

Transfer Learning was explored to utilize pretrained knowledge for sound classification.

- Transfer Learning — 97.10%

## 🔗 Hybrid Learning

Several hybrid architectures were investigated:

- CNN + LSTM — 84%
- CNN + Attention — 92%
- CNN + VGG16 — 90%
- CNN + VGG19 — 97%
- ResNet + SE — 97%

## 📊 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC

## 🚨 Final Output

The final system provides a binary classification:

**Safe / Unsafe**

## 🛠️ Technologies Used

- Python
- Google Colab
- Librosa
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## 👩‍💻 Author

**Sabrina Shanta**
