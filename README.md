# Age, Gender, and Emotion Detection | Computer Vision

## Overview
This project is a real-time system that detects age, gender, and emotions from live video feeds using TensorFlow, OpenCV, and MTCNN for face detection. The models are trained using the UTKFace and CKPlus datasets and deployed on the web using Django.

## Features
✅ Detects age, gender, and emotions from real-time video streams  
✅ Uses MTCNN for accurate face detection  
✅ Achieves high accuracy:
- **Age Detection**: 88.5%
- **Gender Classification**: 84.4%
- **Emotion Recognition**: 90.1%
✅ Web-based deployment for easy accessibility  

## Technologies Used
- **TensorFlow** – Model training and inference
- **OpenCV** – Image processing and video handling
- **MTCNN** – Face detection
- **Django** – Web application backend
- **UTKFace & CKPlus** – Datasets for training

## Installation

### Prerequisites
Ensure you have Python installed (Python 3.8 or higher recommended). Install the required dependencies using:
```bash
pip install -r requirements.txt
```

### Clone the Repository
```bash
git clone https://github.com/yourusername/age-gender-emotion-detection.git
cd age-gender-emotion-detection
```

## Usage

### Running the Application
```bash
python manage.py runserver
```
Then, open `http://127.0.0.1:8000/` in your browser to use the web-based system.

### Running on Live Video
Ensure your webcam is connected and execute:
```bash
python live_detection.py
```

## Dataset
- **UTKFace**: Used for age and gender classification.
- **CKPlus**: Used for emotion recognition.

## Results
The trained models achieve the following accuracies:
- **Age Detection**: 88.5%
- **Gender Classification**: 84.4%
- **Emotion Recognition**: 90.1%

## Contributing
Feel free to fork this repository, create a branch, and submit a pull request for improvements.


## Contact
For any queries, feel free to reach out at [sumat4421@gmail.com].

