**Pretrained Convolutional Neural Network-Based Breast Cancer Classification**
Overview

This project focuses on automated breast cancer classification using Histopathological Images from the BreakHis dataset. The system utilizes pretrained deep learning models such as ResNet and EfficientNet along with transfer learning techniques to classify breast tumor images into benign and malignant categories.

The project also includes:

Image preprocessing and augmentation
Model training and evaluation
Performance comparison of pretrained CNN models
Explainable AI techniques such as Grad-CAM, SHAP, and LIME
Dataset

Dataset Used: BreakHis (Breast Cancer Histopathological Database)

Total Images: 7,909
Classes:
Benign
Malignant
Magnification Levels:
40X
100X
200X
400X

Dataset Source:
Kaggle BreakHis Dataset (https://www.kaggle.com/datasets/waseemalastal/breakhis-breast-cancer-histopathological-dataset)

Hardware
Kaggle GPU (Tesla T4 / P100)
Local GPU (Optional)


**Project Structure** 

Pretrained-Convolutional-Neural-Network-Based-Breast-Cancer-Classification/
│
├── notebooks/
│   └── model_training.ipynb
│
├── dataset/
│
├── saved_models/
│
├── outputs/
│   ├── confusion_matrix/
│   ├── gradcam/
│   ├── shap/
│   └── lime/
│
├── requirements.txt
├── README.md
└── .gitignore


**Setup on Kaggle Environment**
Step 1: Open Kaggle

Visit:
https://www.kaggle.com/

Step 2: Create New Notebook
Click Code
Select New Notebook

Step 3: Enable GPU
Open Notebook Settings
Accelerator → Select GPU

Recommended:

Tesla T4
P100

Step 4: Add Dataset
Click Add Input
Search for:
BreakHis Dataset
Add dataset to notebook
Step 5: Clone Repository

Run:

!git clone https://github.com/Rohit-0112/Pretrained-Convolutional-Neural-Network-Based-Breast-Cancer-Classification.git

Step 6: Install Dependencies
!pip install -r Pretrained-Convolutional-Neural-Network-Based-Breast-Cancer-Classification/requirements.txt

Step 7: Run Notebook
Open:
notebooks/model_training.ipynb

Run all cells sequentially.

**Setup on Local Environment**

Step 1: Clone Repository
git clone https://github.com/Rohit-0112/Pretrained-Convolutional-Neural-Network-Based-Breast-Cancer-Classification.git
Step 2: Navigate to Project Folder
cd Pretrained-Convolutional-Neural-Network-Based-Breast-Cancer-Classification
Step 3: Create Virtual Environment
Windows
python -m venv venv
venv\Scripts\activate
Linux / MacOS
python3 -m venv venv
source venv/bin/activate
Step 4: Install Dependencies
pip install -r requirements.txt
Recommended Python Version
Python 3.10+
Step 5: Launch Jupyter Notebook
jupyter notebook

Open:

notebooks/model_training.ipynb
