# 🩺 Breast Cancer Diagnosis using Machine Learning

This repository contains a machine learning project focused on predicting whether a breast tumor is **benign** or **malignant** using diagnostic data. The project includes data preprocessing, model training, evaluation, and visual exploration.

---

## 📘 Project Overview

Breast cancer is one of the leading causes of death worldwide. Early detection significantly increases treatment success.
This project uses machine learning techniques to analyze diagnostic features and classify tumor types.

The full workflow is implemented in **`BreastCancer_Diagnosis.ipynb`**.

---

## 🧠 Features & Workflow

### ✔️ 1. Data Loading

* Reads dataset from `Dataset.csv`
* Diagnoses encoded using `LabelEncoder`

### ✔️ 2. Preprocessing

* Feature scaling using **MinMaxScaler**
* Splitting the dataset into:

  * **80% training data**
  * **20% test data**

### ✔️ 3. Model Training

* Applies exploratory clustering using **KMeans**
* Builds classification model based on cluster outputs or transformed features

### ✔️ 4. Evaluation Metrics

The model reports:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-score**

These metrics help measure model reliability and real-world usability.

---

## 📂 Repository Structure

```
📁 BreastCancer-Diagnosis-ML
 ├── BreastCancer_Diagnosis.ipynb
 ├── Dataset.csv
 └── README.md
```

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-Learn (`LabelEncoder`, `MinMaxScaler`, `train_test_split`, `KMeans`)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
jupyter notebook BreastCancer_Diagnosis.ipynb
```

---

## 📈 Output

```
Accuracy : 0.9736842105263158
Precision: 0.9761904761904762
Recall   : 0.9534883720930233
F1-score : 0.9647058823529412
```

---

## 🧩 Future Improvements

* Add more classification algorithms (SVM, Random Forest, XGBoost)
* Use grid search for hyperparameter optimization
* Add correlation heatmaps and data visualizations
* Deploy as an API or simple web app for predictions

---

## 📜 License

This project is free to use under the **MIT License**.

---
