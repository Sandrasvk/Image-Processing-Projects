# Image-Processing-Projects


This repository showcases two distinct approaches to Computer Vision: automated image manipulation using pre-trained classifiers and supervised machine learning for multiclass object recognition.

## 📂 Project 1: License Plate Privacy Masking
*Goal:* Automate the detection and blurring of vehicle license plates for privacy compliance.

### Technical Highlights:
* *Detection:* Utilizes Haar Cascade classifiers to identify Russian license plates in complex traffic scenes.
* *Processing:* Implements NumPy slicing to isolate the Region of Interest (ROI) without affecting the background.
* *Filtering:* Applies a Median Blur to the plate area to ensure unreadable text while maintaining image integrity.

## 📂 Project 2: Fruit Classification using Random Forest
*Goal:* Build an end-to-end Machine Learning pipeline to classify images of Mangoes, Oranges, and Cherries.

### Technical Highlights:
* *Data Ingestion:* Automated path handling using the glob module for scalable directory reading.
* *Preprocessing:* Resized all input images to a uniform $400 \times 400$ resolution and flattened 3D pixel arrays for ML compatibility.
* *Model:* Trained a *Random Forest Classifier* to handle multiclass identification.
* *Metrics:* Evaluated using a Confusion Matrix and Classification Report (Achieved 88% precision on Cherry detection).

### Tech Stack:
* *Libraries:* OpenCV, Scikit-Learn, NumPy, Matplotlib, Seaborn.
* *Tools:* Jupyter Notebook, VS Code.
