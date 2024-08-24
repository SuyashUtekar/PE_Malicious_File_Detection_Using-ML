<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<div id="badges" align="center">
  <a href="your-linkedin-URL">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="your-youtube-URL">
    <img src="https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white" alt="Youtube Badge"/>
  </a>
  <a href="your-twitter-URL">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SuyashUtekar&style=flat-square&color=blue" alt=""/>
</p>

<h1 align="center">
  hey there
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

# PE_Malicious_File_Detection_Using-ML_and_DL
---
### :man_technologist: Overview :
This repository contains a sophisticated solution for detecting malicious files using Machine Learning (ML) and Deep Learning (DL) techniques. The project leverages various algorithms to identify potentially harmful files and improve cybersecurity measures.

### :telescope: Feature Selection Methods:

-  Extra Trees Classifier
- Correlation Analysis
- SelectKBest
- Principal Component Analysis (PCA)

### :seedling: Machine Learning Algorithms:

- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Gaussian Naive Bayes (GNB)
- K-Nearest Neighbors (KNN)
- XGBoost
- Logistic Regression

### :zap: Deep Learning Models:

- Artificial Neural Networks (ANN)
- Feedforward Neural Networks (FNN)

## :hammer_and_wrench: Languages and Tools :
<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original-wordmark.svg" title="TensorFlow" alt="TensorFlow" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/keras/keras-original.svg" title="Keras" alt="Keras" width="40" height="40"/>&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Google_Colaboratory_SVG_Logo.svg" title="Google Colab" alt="Google Colab" width="40" height="40"/>&nbsp;
</div>

---

## :fire: My Stats :
[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=SuyashUtekar&theme=dark&background=000000)](https://git.io/streak-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SuyashUtekar&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

---

## 🚀 Implementation :

To execute the implementation of this project, follow these steps:

1. **Run All Cells in `main_implementation.ipynb`:**
   - This Jupyter Notebook contains the complete workflow for the project, including:
     - **Data Preprocessing:** Prepare the data for analysis by cleaning and normalizing it.
     - **Feature Selection:** Evaluate and apply the feature selection methods listed above (Extra Trees Classifier, Correlation Analysis, SelectKBest, PCA).
     - **Model Training:** Train all the ML models mentioned above (Decision Tree, Random Forest, etc.) using each feature selection method.
     - **Performance Evaluation:** Determine which feature selection method allows each model to perform the best.

2. **Save the Results:**
   - After determining the best-performing feature selection method for each model, create a dataset with those features.
   - Save the dataset to a file named `features.pkl`.
   - Save the best-performing model to a file named `model.pkl`.

3. **Final Implementation:**
   - In the last cell of the Notebook, you can test the system by providing a file to the model.
   - The model will predict whether the given file is malicious or not, based on the trained models and selected features.

These steps ensure that the model is accurately trained and can effectively predict malicious files, thus contributing to enhanced cybersecurity measures.


