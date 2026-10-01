# 🩺 Liver Disease Prediction Using Machine Learning

A machine learning-based application for predicting the possibility of liver disease from patient medical data.

The project implements multiple machine learning algorithms, compares their performance, and provides a user-friendly desktop interface for dataset preprocessing, model training, evaluation, and prediction.

---

## 📌 Project Overview

Liver diseases can be difficult to identify at an early stage because symptoms may not always be obvious.

This project uses **Machine Learning classification techniques** to analyze patient-related medical attributes and predict whether a patient is likely to have liver disease.

The application provides an interactive interface where users can:

- 📂 Upload a dataset
- 🔄 Preprocess the dataset
- 🤖 Train machine learning models
- 📊 Evaluate model performance
- 📈 Visualize results
- 🔮 Make predictions
- 🧠 Use an Artificial Neural Network model

> **Note:** This project is intended for educational and research purposes. It is not a medical diagnostic tool.

---

## 🎯 Objectives

- Develop a machine learning system for liver disease prediction.
- Preprocess and analyze medical datasets.
- Train multiple classification algorithms.
- Compare model performance using evaluation metrics.
- Provide a simple graphical user interface.
- Demonstrate how machine learning can assist healthcare-related data analysis.

---

## 🧠 Machine Learning Algorithms

The project works with classification algorithms including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Naive Bayes
- XGBoost
- Artificial Neural Network (ANN)

---

## 🔄 Project Workflow

```text
Patient Dataset
      ↓
Upload Dataset
      ↓
Data Preprocessing
      ↓
Data Cleaning
      ↓
Feature Selection
      ↓
Train/Test Split
      ↓
Machine Learning Models
      ↓
Model Evaluation
      ↓
Performance Comparison
      ↓
Liver Disease Prediction
```

---

## 📊 Dataset

The project uses a liver disease dataset containing patient-related medical attributes.

Example attributes include:

- Age
- Gender
- Total Bilirubin
- Direct Bilirubin
- Alkaline Phosphatase
- Alanine Aminotransferase (ALT/SGPT)
- Aspartate Aminotransferase (AST/SGOT)
- Total Protein
- Albumin
- Albumin and Globulin Ratio

The dataset is included in the `dataset` directory.

---

## 🖥️ Application Interface

The application provides a graphical interface with options for:

### Upload Dataset
Select the input medical dataset.

### Preprocess Dataset
Prepare the raw data for machine learning by performing the required preprocessing operations.

### Train Models
Train different machine learning algorithms using the processed dataset.

### Evaluate Models
Analyze model performance using classification metrics and visualizations.

### Prediction
Use the trained model to predict the possibility of liver disease based on patient information.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- XGBoost
- TensorFlow
- Keras

### Data Processing
- NumPy
- Pandas

### Visualization
- Matplotlib
- Seaborn
- Scikit-plot

### GUI / Utilities
- Tkinter
- Imutils

### Development Tools
- Jupyter Notebook
- VS Code
- Git
- GitHub

---

## 📁 Project Structure

```text
liver-disease-prediction/
│
├── dataset/
│   └── ALF_Data.xlsx
│
├── LDP.py
├── LDP.ipynb
├── model_ann.h5
├── run.bat
├── Liver Disease Prediction.docx
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the project

```bash
cd "liver disease prediction"
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

#### Windows PowerShell

```powershell
.\.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install numpy pandas scikit-learn matplotlib seaborn xgboost tensorflow keras imutils openpyxl scikit-plot
```

---

## ▶️ Run the Application

After activating the virtual environment:

```bash
python LDP.py
```

Alternatively, you can run:

```bash
run.bat
```

---

## 📈 Model Evaluation

The project evaluates machine learning models using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC

These metrics help analyze how effectively each model performs on the dataset.

---

## 🧪 Example Prediction Flow

```text
Patient Information
        ↓
Feature Processing
        ↓
Trained ML Model
        ↓
Prediction
        ↓
Liver Disease / No Liver Disease
```

The prediction should be interpreted as a **machine learning output**, not as a medical diagnosis.

---

## 🚀 Future Improvements

Possible improvements include:

- Web-based deployment using Streamlit or Flask
- Improved model optimization
- Hyperparameter tuning
- Feature importance analysis
- Explainable AI (XAI)
- SHAP/LIME-based explanations
- Larger and more diverse datasets
- Cloud deployment
- Mobile-friendly prediction interface

---

## 👨‍💻 Author

**Rakesh Chowdary**

B.Tech – Computer Science Engineering  
AI & Machine Learning / Data Science Enthusiast

---

## 📜 Disclaimer

This project is developed for **educational and research purposes only**.

The predictions generated by this application should not be used as a substitute for professional medical diagnosis, medical advice, or treatment.

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.<img width="637" height="359" alt="Screenshot 2026-10-01 232614" src="https://github.com/user-attachments/assets/628bf18d-581b-4bf2-b44b-9ef966d9731c" />
