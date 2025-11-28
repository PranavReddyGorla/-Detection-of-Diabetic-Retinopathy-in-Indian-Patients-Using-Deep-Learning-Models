🩺 Detection of Diabetic Retinopathy in Indian Patients Using Machine Learning Models

A machine learning project focused on early detection of Diabetic Retinopathy (DR) from retinal fundus images of Indian patients.
The project uses image preprocessing, feature extraction, and classical machine learning algorithms to classify DR severity levels.

🧾 Project Overview

Diabetic Retinopathy is one of the leading causes of vision loss in India. Early identification is crucial for timely treatment.
This project presents an ML-based solution to detect DR severity using:
Image preprocessing (OpenCV)
Feature extraction
Machine learning classification (SVM, Random Forest, KNN)
A simple web interface for predictions (HTML + CSS)
The system is built specifically for Indian patient datasets, increasing its practical value in real-world clinical scenarios.

✨ Features

✔ Preprocessing of retinal fundus images
✔ Feature extraction & dataset creation
✔ ML model training using Scikit-learn
✔ Classification across multiple DR severity levels
✔ A clean web interface for predictions
✔ Model benchmarking & comparison

🛠 Tech Stack

Programming Language:
-Python
Libraries & Tools:
-OpenCV
-Pandas
-NumPy
-Scikit-learn
Frontend:
-HTML
-CSS
Domain:
-Healthcare
-Machine Learning

🔬 Methodology
1. Image Preprocessing (OpenCV)
Applied CLAHE for contrast enhancement
Removed noise using Gaussian/Median filters
Resized images to uniform dimensions
Extracted pixel, color, and texture features

2. Feature Engineering
Extracted features using:
Color histograms
Texture features (GLCM)
Intensity-based metrics
Features stored in a Pandas DataFrame for training.

3. Model Training (Scikit-learn)
Implemented multiple ML algorithms:
Model	Purpose
SVM	High accuracy for complex decision boundaries
Random Forest	Robust and interpretable
KNN	Baseline comparison

📁 Project Structure

project/
│── app.py
│── svm_classifier.py
│── random_forest.py
│── knn.py
│── GA.py
│── mlp_classifier.py
│── database.txt
│── system_architecture.png
│── Diabetics.xlsx
│── cart.py
│
├── static/
├── templates/
├── models/
├── features/

📊 Results

Successfully classified Diabetic Retinopathy into severity levels
Compared accuracy, precision, recall for SVM, Random Forest, KNN
Achieved strong results suitable for academic demonstration
Provided visual predictions through a web interface
