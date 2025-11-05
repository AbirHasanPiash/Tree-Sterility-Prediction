# Tree Sterility Prediction using Machine Learning

## Description
This project focuses on predicting **tree sterility** (Sterile vs. Non-Sterile) using supervised and unsupervised machine learning techniques. The study was conducted as part of a machine learning research effort to explore how ecological and experimental factors — such as soil type, mycorrhizal associations, and light conditions — influence plant sterility outcomes.

The dataset contains **2,783 observations and 24 features**, including both categorical and numerical variables. After comprehensive data cleaning, preprocessing, and exploratory data analysis (EDA), several models were developed and compared for performance.

Supervised algorithms such as **Logistic Regression, Decision Tree, K-Nearest Neighbors (KNN), Gaussian Naïve Bayes, and Multilayer Perceptron (MLP)** were implemented. All models achieved exceptional performance, with **Logistic Regression, Decision Tree, and GaussianNB reaching perfect classification accuracy (100%) and ROC–AUC = 1.0**.  
Additionally, **K-Means clustering** was applied to assess inherent patterns in the data, confirming strong natural separability between the two classes.

The entire analysis — from preprocessing to model evaluation — was performed in **Python (Scikit-learn, Pandas, NumPy, Matplotlib)** using **Google Colab**.

## Dataset
The dataset consists of both **categorical** and **numerical** features related to ecological and experimental conditions.  
Key attributes include:
- **Light ISF**, **Soil**, **Myco**, **Phenolics**, **Lignin**, **NSC**, and **Census Time**
- The target variable: **Sterile** (binary — Sterile or Non-Sterile)
[Dataset](https://drive.google.com/file/d/1-cWAGN22-OrZhLLLXiKY1V7XIp88ZOrf/view?usp=sharing)

Due to data confidentiality, the original dataset cannot be shared publicly. However, the structure and preprocessing steps are fully documented in the notebook.

## Research Report (PDF)
[Predicting Tree Sterility Using Machine Learning](https://drive.google.com/file/d/1s0oDjSz8ez589mD72Fh1e04iW-zaeZoB/view?usp=sharing)

## Key Features
- End-to-end **supervised ML pipeline** with data preprocessing, encoding, and scaling  
- **Cross-validation and stratified splits** to handle class imbalance (85:15 ratio)  
- Evaluation of five classical ML algorithms with detailed performance comparison  
- Implementation of **K-Means clustering** for unsupervised validation  
- Achieved **100% accuracy** on test data for multiple models  
- Insightful discussion on feature importance and ecological interpretation  

## Technologies Used
- **Python**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

## Author
**Md. Abir Hasan Piash**  
📧 abirhasanpiash@gmail.com 
🔗 [LinkedIn](https://linkedin.com/in/a-h-piash)
