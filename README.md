# Real-Time Emotion Tracking from Video Frames (Facial Expression + LSTM)

This project implements a real-time facial expression recognition system using Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) models. The system processes video frames to detect and classify human emotions such as **happy**, **sad**, **angry**, and more.

## Project Description

The aim is to combine spatial features (from face images) and temporal features (across frames) using CNN + LSTM to recognize emotions over time.

The notebook follows a structured pipeline:
1. **Dataset selection & preprocessing**
2. **Face detection using MTCNN**
3. **Data augmentation**
4. **Feature extraction with CNN**
5. **Emotion classification with LSTM**
6. **Evaluation using accuracy, precision, recall, and F1-score**

## Technologies Used

- Python 3.11+
- TensorFlow / Keras
- OpenCV
- MTCNN
- NumPy / Pandas / Matplotlib
- scikit-learn

## Dataset

The project uses an emotion recognition dataset with labeled video frames. Preprocessing steps include:
- Cropping faces with MTCNN
- Normalization & resizing
- Frame sequencing for temporal modeling

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/emotion-lstm-tracker.git
cd emotion-lstm-tracker
pip install -r requirements.txt
