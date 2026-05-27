# Iris Flower Classification

## Project Overview
This project uses Machine Learning to classify Iris flower species based on flower measurements.

The model predicts whether a flower belongs to:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

using:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

# Machine Learning Algorithm

K-Nearest Neighbors (KNN) Classifier

KNN predicts the class of a flower based on the nearest neighboring data points.

---

# Dataset

The Iris dataset contains:
- 150 flower samples
- 4 input features
- 3 output classes

Dataset source:
Scikit-learn Iris Dataset

---

# Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Train-Test Split
4. Feature Scaling
5. Model Training using KNN
6. Prediction
7. Model Evaluation

---

# Feature Scaling

StandardScaler was used to normalize feature values for better distance calculation in KNN.

---

# Model Evaluation

Evaluation metrics used:
- Accuracy Score
- Classification Report
- Confusion Matrix

Achieved Accuracy:
100%

---

# Project Structure
├── internship_task-1.ipynb
├── Iris.csv
├── README.md---

# How to Run

## Install Dependencies

```bash
pip install pandas numpy scikit-learn
jupyter notebook

```md
internship_task-1.ipynb---

# Output

The trained model successfully classifies Iris flower species with high accuracy.

---

# Author

Nensi Patel
