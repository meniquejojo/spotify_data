# Spotify Data Project

This project explores Spotify listening data and applies machine learning techniques to build predictive models and visualizations. The focus is on understanding patterns in user behavior, audio features, and song characteristics using Python and popular data science libraries.

## 📌 Project Overview

The goal of this project is to:

* Load and clean Spotify data
* Perform exploratory data analysis (EDA)
* Visualize trends and patterns
* Train predictive models for classification or regression tasks
* Evaluate model performance using metrics like accuracy, ROC-AUC, confusion matrix, and classification report

## 📂 Features

* Data preprocessing (handling missing values, feature scaling, encoding)
* Exploratory visualizations (correlation heatmaps, scatterplots, histograms)
* Model training using scikit-learn
* Evaluation using cross-validation and ROC curves
* Custom model evaluation functions

## 🧰 Tech Stack

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

## 📊 Machine Learning Models Used

* Logistic Regression
* Random Forest Classifier
* Support Vector Machines (SVM)
* Decision Trees
* K-Nearest Neighbors

## 🧪 Model Evaluation

The following metrics were used:

* Accuracy Score
* Classification Report
* Confusion Matrix
* ROC Curve & AUC Score

## 📁 Project Structure

```
📦 spotify-data-project
 ┣ 📜 data.csv
 ┣ 📜 notebook.ipynb
 ┣ 📜 model.py
 ┣ 📜 visualizations.py
 ┗ 📜 README.md
```

## 🚀 How to Run

1. Clone the repository:

```
git clone https://github.com/yourusername/spotify-data-project.git
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```
jupyter notebook
```

## 📈 Results

* Visual insights on audio features
* Performance comparison of models
* Best-performing model based on ROC-AUC and cross-validation

## 📌 Next Steps

* Build a personalization model that predicts if a user will skip a song
* Expand dataset with user interactions
* Deploy model using Flask or FastAPI
* Add a dashboard (Streamlit)

## 🙌 Acknowledgements

* Spotify Developer Data
* Zero to Mastery Machine Learning Course

---

Feel free to contribute or raise issues for improvements!
