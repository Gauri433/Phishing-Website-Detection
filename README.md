Phishing Detection Using CNN-BiLSTM with Meta-Learning
Overview
Phishing attacks are a prevalent cybersecurity threat, leading to financial losses and stolen personal data. This project provides a deep learning-based system to detect phishing websites with high accuracy. It leverages a hybrid CNN-BiLSTM model, enhanced with meta-learning, to distinguish phishing websites from legitimate ones effectively. The system is integrated into a user-friendly Flask web application that allows users to paste URLs and check their authenticity.

Features
Deep Learning Model: Combines CNN for spatial feature extraction and BiLSTM for sequential pattern recognition.
Meta-Learning: Utilizes the Reptile algorithm for quick adaptation to diverse phishing patterns.
Web Application: A Flask-based interface for users to easily check website authenticity.
High Accuracy: Demonstrates superior performance on a comprehensive dataset of phishing and legitimate URLs.
Scalable and Robust: Designed to handle diverse phishing scenarios effectively.
Technologies Used
Programming Language: Python
Frameworks: TensorFlow/Keras, Flask
Deep Learning Techniques:
Convolutional Neural Networks (CNN)
Bidirectional Long Short-Term Memory (BiLSTM)
Meta-learning with Reptile algorithm
Dataset: Kaggle dataset of phishing and legitimate URLs
Installation
Prerequisites
Python 3.8 or later
Libraries: TensorFlow, Flask, NumPy, Pandas, Scikit-learn
Steps
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/phishing-detection.git
cd phishing-detection
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Start the Flask web application:
bash
Copy code
python app.py
Open your browser and navigate to http://127.0.0.1:5000.
Usage
Open the web application.
Paste the URL you want to verify into the input field.
Click "Check URL" to get immediate feedback on whether the site is legitimate or a phishing attempt.
Model Architecture
CNN-BiLSTM Hybrid Model: Extracts spatial features and sequential patterns for phishing detection.
Meta-Learning: Adapts the model to handle new phishing patterns with minimal data.
