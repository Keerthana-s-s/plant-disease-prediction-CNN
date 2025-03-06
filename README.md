**🌿 Plant Disease Detection System for Sustainable Agriculture**


**📌 Overview**
This project implements a Convolutional Neural Network (CNN)-based model to detect and classify plant diseases using leaf images. The system aims to enhance precision agriculture by enabling early detection and effective disease management.


**🔍 Problem Statement**
Detect and classify plant diseases from images of leaves across various crops such as apple, cherry, grape, and corn.
Differentiate between healthy and diseased leaves while identifying the specific type of disease.
Aid farmers in early detection and disease control for improved crop yield.


**💡 Solution Approach**
A CNN-based deep learning model trained on a labeled dataset of plant leaves (both healthy and diseased).
The model processes images, classifies plant diseases, and predicts outcomes with high accuracy.
The project includes a Streamlit web application for real-time image-based disease detection.


**🛠️ Tech Stack**
Programming Language: Python
Machine Learning Framework: TensorFlow / Keras
Image Processing: OpenCV
Web Framework: Streamlit
Dataset: Kaggle - New Plant Diseases Dataset (Augmented)


**📂 Project Structure**
CNN Model: Trains a deep learning model for disease classification.
Model Training: Uses TensorFlow/Keras with data augmentation for improved accuracy.
Evaluation: Includes metrics such as accuracy, precision, and recall.
Web App (Streamlit): Allows users to upload leaf images and get disease predictions.
🖥️ Hardware & Software Requirements
✅ Minimum Requirements

**Hardware:**
Processor: Intel i5 or higher
RAM: 8GB (16GB recommended)
Storage: Minimum 100GB
GPU: NVIDIA GTX 1050 or higher (recommended for training)

**Software:**
OS: Windows 10, Linux, or macOS
Python 3.8+
TensorFlow 2.x / PyTorch
OpenCV for image processing


**🚀 How to Run**

**Clone the repository:**
git clone https://github.com/yourusername/plant-disease-prediction-CNN.git
cd plant-disease-detection
**Install dependencies:**
pip install -r requirements.txt
**Run the Streamlit app:**
streamlit run app.py

**📊 Model Performance**
The CNN model achieves high accuracy in disease classification.
Evaluated using precision, recall, and validation loss metrics.

**🎯 Future Scope**
Implementing transfer learning with models like InceptionV3 or ResNet.
Mobile application integration for on-the-go plant disease detection.
Expanding the dataset for more plant species.
