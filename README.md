# 🎬 Movie Genre Classification

## 📌 Project Overview

This project is developed as **Task 1** for the **CodSoft Machine Learning Internship**.

The objective of this project is to build a Machine Learning model that predicts the **genre of a movie** based on its plot summary using Natural Language Processing (NLP) techniques.

---

## 📂 Repository Name

CODSOFT_TASK1

---

## 🎯 Objective

To develop a machine learning model that can automatically classify a movie into its correct genre using its plot description.

---

## 📊 Dataset

Dataset Used:
IMDb Genre Classification Dataset

Kaggle Dataset Link:
https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

### Dataset Files

The project uses the following files:

- train_data.txt
- test_data.txt
- test_data_solution.txt

> **Note:**  
> The dataset files are not included in this repository because GitHub's web upload has a file size limit. Download the dataset from the Kaggle link above and place the files inside a folder named `dataset`.

Project Structure:

```
CODSOFT_TASK1
│
├── dataset
│   ├── train_data.txt
│   ├── test_data.txt
│   └── test_data_solution.txt
│
├── movie_genre_classification.ipynb
├── requirements.txt
├── README.md
└── description.txt
```

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression
- Jupyter Notebook

---

## 📚 Machine Learning Workflow

1. Load the dataset
2. Preprocess the movie descriptions
3. Convert text into numerical features using TF-IDF Vectorization
4. Train the Logistic Regression model
5. Predict movie genres
6. Evaluate the model using Accuracy Score

---

## 🤖 Machine Learning Model

### Feature Extraction

- TF-IDF (Term Frequency–Inverse Document Frequency)

### Classification Algorithm

- Logistic Regression

---

## 📈 Model Performance

**Accuracy Achieved**

```
58.36%
```

---

## 🎯 Sample Prediction

### Input

```
A detective investigates mysterious murders in New York.
```

### Predicted Genre

```
Thriller
```

---

## ▶️ How to Run the Project

### Step 1

Clone the repository

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/CODSOFT_TASK1.git
```

### Step 2

Go to the project folder

```bash
cd CODSOFT_TASK1
```

### Step 3

Install the required libraries

```bash
pip install -r requirements.txt
```

### Step 4

Download the dataset from Kaggle and place the files inside the `dataset` folder.

### Step 5

Open the notebook

```
movie_genre_classification.ipynb
```

Run all the cells.

---

## 📋 Requirements

```
pandas
numpy
scikit-learn
matplotlib
```

---

## 📁 Project Files

```
movie_genre_classification.ipynb
requirements.txt
README.md
description.txt
dataset/
```

---

## 🚀 Future Improvements

- Use Support Vector Machine (SVM)
- Use Random Forest Classifier
- Apply Deep Learning (LSTM)
- Use Word2Vec or BERT embeddings
- Improve prediction accuracy through hyperparameter tuning

---

## 📸 Output

```
Accuracy: 0.5836162361623616

Predicted Genre: thriller
```

---

## 👨‍💻 Author

**Anand Kumar**

B.Tech (Artificial Intelligence & Machine Learning)

CodSoft Machine Learning Intern

---

## 📄 License

This project is created for educational purposes as part of the **CodSoft Machine Learning Internship**.
