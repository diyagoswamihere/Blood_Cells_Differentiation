# Blood_Cells_Differentiation
A deep learning-based system for classifying blood cells using MobileNet

🧪 An AI-Powered Blood Cell Analyzer

A deep learning-based system that classifies different types of blood cells (WBCs, RBCs, platelets) using microscopic images. Built using MobileNet and deployed with Streamlit for interactive demos.

🔍 Project Overview

- Goal:Automate blood smear analysis to assist in medical diagnostics.
- Dataset: [Blood Cell Dataset from Kaggle] https://www.kaggle.com/paultimothymooney/blood-cells
- Tech Stack:
  - Python, TensorFlow/Keras
  - MobileNetV2 / ResNet for feature extraction
  - Streamlit for UI deployment

📁 Folder Structure
├── BloodCellsDifferentiation.ipynb
├── sample_outputs/
│ ├── ClassificationReport.png
│ └── ConfusionMatrix.png
├── requirements.txt

📊 Model Performance
Architecture: MobileNetV2 + GlobalAveragePooling + Dense layers
Optimizer: Adam
Accuracy: ~95% on test dataset
Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report

💡 Features
Image preprocessing (resizing, normalization)
Automatic label encoding from folder names
Real-time predictions on uploaded images
Detailed visualizations of model performance

🧩 Future Enhancements
Streamlit web app integration for easy access
Add more blood disorders to classification categories
Model deployment on Hugging Face Spaces or Streamlit Cloud

📌 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Diya Goswami
