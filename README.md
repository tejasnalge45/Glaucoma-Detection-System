# Glaucoma-Detection-System
Glaucoma Detection System
Overview

This is an AI-powered web application for Glaucoma detection using Retinex-enhanced fundus images and an optimized CNN (Convolutional Neural Network) model. The system helps in early-stage diagnosis by analyzing retinal images and predicting whether a patient has glaucoma.
Features

✔ Deep Learning-based Glaucoma Detection using TensorFlow/Keras
✔ Retinex Image Enhancement for better feature extraction
✔ Web-based Interface built with Flask/Django, HTML, CSS, JavaScript
✔ Real-time Image Upload & Analysis
✔ Performance Metrics: Accuracy, Sensitivity, Specificity
Technologies Used

    Frontend: HTML, CSS, JavaScript
    Backend: Flask/Django
    Machine Learning: TensorFlow/Keras, OpenCV
    Database: SQLite/MySQL
    Cloud Deployment (Optional): AWS/GCP

Installation & Setup
1. Clone the Repository

git clone https://github.com/your-username/Glaucoma-Detection-System.git
cd Glaucoma-Detection-System

2. Install Dependencies

pip install -r requirements.txt

3. Run the Application

python app.py

The web app will be available at http://127.0.0.1:5000/.
Dataset & Model

    The model is trained on a fundus image dataset using CNN architecture.
    You can download the trained model (glaucoma_model.h5) from the repository and place it in the models/ directory.



Add images of the web interface and prediction results here.
Future Enhancements

🔹 Deploying on AWS/GCP for cloud-based detection
🔹 Improving model accuracy with transfer learning
🔹 Adding a feature for doctor consultations
