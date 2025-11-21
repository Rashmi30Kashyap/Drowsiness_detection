## Drowsiness Detection System using CNN, OpenCV & Streamlit
A real-time Driver Drowsiness Detection System built using Python, TensorFlow/Keras, OpenCV, and Streamlit.
The system monitors eye activity using a trained CNN model, calculates EAR (Eye Aspect Ratio), and raises alerts when drowsiness is detected.
Supports detection through images, videos, webcam, and IP camera streams with a live dashboard

## Features
### Image Upload Detection
Detect drowsiness in uploaded images.
### Video Upload Detection
Analyze pre-recorded videos frame-by-frame.
### Webcam Detection
Real-time monitoring using system webcam.
### IP Camera Detection
Supports remote video streams through IP cameras.
### Responsive Interface
Built with Streamlit + custom background image.

## Model Overview
CNN model trained on MRL Eye Dataset (Kaggle)
Input size: 64×64 grayscale images
Output classes:
1 → Open Eye (Awake)
0 → Closed Eye (Drowsy)
Achieved ~97% accuracy during training

## Technologies Used
Python 3.12
TensorFlow / Keras
OpenCV
Streamlit
NumPy, Matplotlib
MRL Eye Dataset

## Required libraries:
tensorflow
opencv-python
streamlit
numpy
matplotlib
pillow

## Screenshots 

### Model Training 


<img width="1038" height="709" alt="Screenshot 2025-11-11 at 6 42 17 PM" src="https://github.com/user-attachments/assets/53c4cd09-e9a8-42a2-8528-0b9c705285ad" />

### Streamlit Dashboard


<img width="1393" height="774" alt="Screenshot 2025-11-12 at 12 18 12 AM" src="https://github.com/user-attachments/assets/9848363a-d8b3-4650-b171-c40f35e0c3f8" />




## How It Works
Detects face and eyes using Haar Cascades
Classifies eyes using trained CNN
Calculates EAR for trend monitoring
Triggers alarm if eyes stay closed

## Future Scope
Add yawning & head pose detection
Mobile app deployment (TFLite)
Multi-driver monitoring

## What I Learned
CNN model training & preprocessing
OpenCV-based face/eye detection
Real-time video frame processing
Building interactive dashboards with Streamlit
