## Drowsiness Detection System
A real-time driver drowsiness detection system using CNN, OpenCV, and Streamlit.
It detects whether eyes are open or closed, calculates EAR (Eye Aspect Ratio), and triggers alerts to prevent fatigue-related accidents.
## Features
Image, video, webcam & IP camera detection
CNN-based eye-state classification
EAR calculation with live graph
Audio and visual drowsiness alerts
Streamlit dashboard for real-time monitoring
## Technologies Used
Python, OpenCV, TensorFlow/Keras
Streamlit, NumPy, Matplotlib
MRL Eye Dataset
## How to Run
pip install -r requirements.txt
streamlit run app.py
## How It Works
Detects face and eyes using Haar Cascades
Classifies eyes using trained CNN
Calculates EAR for trend monitoring
Triggers alarm if eyes stay closed
Displays EAR graph & drowsy events
## Future Scope
Add yawning & head pose detection
Mobile app deployment (TFLite)
Multi-driver monitoring
