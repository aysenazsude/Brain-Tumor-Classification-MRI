# Brain-Tumor-Classification-MRI
A Deep Learning project to classify brain tumors into 4 categories using MRI scans. Developed as part of my AI research journey.

## Roadmap for the start
- *Firstly in this project, I want to make a **Flask web application** for uploading a MRI picture and getting the result of the scan in terms of which category it belongs to. So the aim is that building the model and then making the interface.*


## 🛠️ Project Workflow
To ensure a structured and robust development process, the project follows these technical steps:

***CURRENT STEP***
**1. Data Loading:** Load MRI images for training, validation, and testing. Getting other informations about the dataset as picture quality or other factors. Searching for the special attributes about the categories to get better understanding of the underlying patterns.

***NEXT STEPS***
**2. Data Preprocessing:** Apply normalization, resizing, and augmentation techniques.
**3. Model Building:** Build a Convolutional Neural Network (CNN) using PyTorch to classify the MRI images.
**4. Model Training:** Train the model on GPU (if available) to detect brain tumors.
**5. Flask Web Application:** Develop a Flask app for user interaction, allowing image uploads for tumor detection.
**6. Model Deployment:** Deploy the trained model within the Flask app.
**7. Prediction:** Provide real-time predictions through the Flask web app.

> **Note on Credits:** The core methodology and structural workflow of this project were inspired by [BRAIN TUMOR DETECTION [END 2 END]]. I would like to acknowledge their work as it provided a valuable framework for this research and helped me gain deeper insights into Medical AI pipelines.
