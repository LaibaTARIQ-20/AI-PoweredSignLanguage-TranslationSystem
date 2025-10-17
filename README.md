AI-Powered Sign Language Translation System
Overview
This repository contains a real-time sign language translation system designed to bridge communication gaps between the deaf/mute and hearing/speaking communities. The project leverages MediaPipe and OpenCV for hand gesture detection and tracking, and uses a Random Forest classifier to accurately translate sign gestures into text and speech. The system is deployed via a Flask web application and is trained on a custom dataset of 14,000 images to enhance accuracy and minimize overfitting.

Features
Real-time sign language detection and translation using webcam input
MediaPipe and OpenCV for robust gesture detection and processing
Random Forest classifier for accurate recognition and translation
Integrated speech and text output for accessibility
Flask-based web app interface for easy deployment and usage
Trained on a custom dataset (14,000 images) for improved accuracy
Tech Stack
Python
Flask
MediaPipe
OpenCV
Scikit-learn (Random Forest)
Numpy, Pandas
Installation
Clone the repository
git clone https://github.com/LaibaTARIQ-20/AI-PoweredSignLanguage-TranslationSystem.git
cd AI-PoweredSignLanguage-TranslationSystem
Install dependencies
pip install -r requirements.txt
Run the application
python app.py
Access the web app at http://localhost:5000.

Usage
Launch the Flask application.
Grant webcam access when prompted.
Sign gestures in front of the camera.
The system will translate gestures to text and optionally to speech output.
Dataset
The model is trained on a custom dataset of 14,000 hand gesture images.
If you need access to the dataset, please contact the repository owner.
Project Structure
AI-PoweredSignLanguage-TranslationSystem/
│
├── app.py
├── requirements.txt
├── README.md
├── model/
│   └── random_forest_model.pkl
├── static/
│   └── (CSS, JS files)
├── templates/
│   └── index.html
└── utils/
    └── (helper scripts)