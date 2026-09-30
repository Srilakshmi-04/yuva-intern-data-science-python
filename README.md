# YuvaIntern – Virtual Data Science with Python Trainee

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Data Science](https://img.shields.io/badge/Data%20Science-Python-orange)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-green)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-PyTorch-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Internship](https://img.shields.io/badge/Internship-YuvaIntern-purple)

---

## 📌 About the Internship

This repository contains my complete project work for the **YuvaIntern – Virtual Data Science with Python Trainee** internship.

The internship was structured as a six-week practical learning program covering the complete Data Science lifecycle using Python. Each week focused on a different stage of the workflow, beginning with data acquisition and preprocessing and progressing toward exploratory data analysis, unsupervised learning, supervised learning, deep learning, and finally an integrated capstone project.

The internship provided hands-on experience in:

- Data acquisition
- Data inspection
- Data cleaning
- Data preprocessing
- Exploratory Data Analysis
- Data visualization
- Unsupervised learning
- Supervised learning
- Deep learning
- Model evaluation
- Performance analysis
- Technical documentation
- End-to-end Data Science pipeline development

---

## 👩‍💻 Intern Information

**Name:** Sri Lakshmi

**Internship:** Virtual Data Science with Python Trainee

**Organization:** YuvaIntern

**Duration:** 6 Weeks

**Start Date:** 30 July 2026

**End Date:** 10 September 2026

---

# 📂 Repository Structure

```text
yuva-intern-data-science-python/
│
├── Week_1_Data_Cleaning_Preprocessing/
│   ├── YuvaIntern_Week1_Data_Cleaning_Preprocessing_Report.docx
│   ├── YuvaIntern_Week1_Data_Cleaning_Preprocessing.ipynb
│   └── YuvaIntern_Week1_Breast_Cancer_Raw.csv
│
├── Week_2_EDA_Visualization/
│   ├── YuvaIntern_Week2_EDA_Visualization_Report.docx
│   ├── YuvaIntern_Week2_EDA_Visualization.ipynb
│   └── YuvaIntern_Week2_Breast_Cancer_Dataset.csv
│
├── Week_3_Unsupervised_Clustering/
│   ├── YuvaIntern_Week3_Unsupervised_Clustering_Report.docx
│   ├── YuvaIntern_Week3_Unsupervised_Clustering.ipynb
│   └── YuvaIntern_Week3_Breast_Cancer_Clustering_Dataset.csv
│
├── Week_4_Supervised_Learning/
│   ├── YuvaIntern_Week4_Supervised_Learning_Report.docx
│   ├── YuvaIntern_Week4_Supervised_Learning.ipynb
│   └── YuvaIntern_Week4_Breast_Cancer_Dataset.csv
│
├── Week_5_Deep_Learning/
│   ├── YuvaIntern_Week5_Deep_Learning_Report.docx
│   ├── YuvaIntern_Week5_Deep_Learning.ipynb
│   └── YuvaIntern_Week5_Digits_Dataset.csv
│
├── Week_6_Integrative_Capstone/
│   ├── YuvaIntern_Week6_Integrative_Capstone_Report.docx
│   ├── YuvaIntern_Week6_Integrative_Capstone.ipynb
│   └── YuvaIntern_Week6_Breast_Cancer_Capstone_Dataset.csv
│
└── README.md


🗓️ Week 1 – Data Acquisition, Cleaning, and Preprocessing
🎯 Objective

The objective of Week 1 was to understand the fundamentals of acquiring, inspecting, cleaning, and preprocessing a real-world dataset.

The project focused on acquiring a publicly available dataset, understanding its structure, identifying data-quality issues, and applying appropriate preprocessing techniques.

This stage established the foundation for the remaining Data Science and machine-learning projects.

📊 Dataset

The Breast Cancer Wisconsin (Diagnostic) dataset was used.

The dataset contains numerical diagnostic measurements along with a binary target variable.

It was selected because it provides a structured dataset suitable for data cleaning, preprocessing, exploratory analysis, clustering, and classification.

🔎 Data Acquisition

The dataset was loaded into Python and converted into a pandas DataFrame.

Initial inspection was performed to understand:

Number of rows
Number of columns
Feature names
Data types
Target variable
Numerical feature distributions

Python libraries including pandas, NumPy, and scikit-learn were used.

🧹 Data Cleaning

Several data-quality checks were performed.

Missing Values

The dataset was checked for missing or null values.

This is important because missing values can affect statistical analysis and machine-learning model performance.

Duplicate Records

Duplicate rows were checked to ensure that the same observation was not unintentionally represented multiple times.

Outlier Detection

Potential outliers were investigated using the Interquartile Range (IQR) method.

The IQR method uses:

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR

Values outside these boundaries were identified as potential outliers.

⚙️ Data Preprocessing

Numerical features were standardized to bring features with different scales to a comparable range.

Standardization is particularly important for algorithms that depend on feature magnitude or distance calculations.

The preprocessing stage prepared the dataset for later analysis and modeling.

📚 Key Learning

Week 1 provided practical understanding of:

Dataset acquisition
Data inspection
Data-quality checking
Missing-value analysis
Duplicate detection
Outlier detection
Feature preprocessing
Standardization
Importance of clean data before modeling
📈 Week 2 – Exploratory Data Analysis and Visualization
🎯 Objective

The objective of Week 2 was to perform Exploratory Data Analysis (EDA) and use visualization techniques to understand the underlying structure, distributions, and relationships within the dataset.

The goal was to convert raw numerical data into meaningful observations before applying machine-learning models.

📊 Dataset

The Breast Cancer Wisconsin (Diagnostic) dataset was used.

Continuing with the same dataset allowed the analysis to build upon the preprocessing work completed during Week 1.

🔍 Exploratory Analysis

The dataset was explored using statistical and visual techniques.

The analysis included:

Dataset dimensions
Data types
Descriptive statistics
Missing-value checks
Duplicate checks
Class distribution
Feature distributions
Relationships between variables
Correlation analysis
📊 Visualizations

Several visualizations were created using Python.

Histogram

Histograms were used to understand the distribution of numerical features.

Scatter Plot

Scatter plots were used to examine relationships between numerical variables.

Correlation Visualization

Correlation analysis was performed to understand relationships among numerical features.

Group-Level Analysis

Feature values were compared across target categories to identify differences between groups.

🧠 Interpretation

EDA helped identify:

Feature distributions
Relationships between variables
Target-class distribution
Potentially useful patterns
Differences between target categories

The analysis helped establish an understanding of the dataset before applying machine-learning techniques.

📚 Key Learning

Week 2 provided practical experience with:

Exploratory Data Analysis
Descriptive statistics
Data visualization
Feature distribution analysis
Correlation analysis
Pattern identification
Interpretation of visualizations
🔵 Week 3 – Unsupervised Learning and Clustering Analysis
🎯 Objective

The objective of Week 3 was to understand unsupervised learning and discover natural patterns or groups within the dataset without using the target variable during clustering.

The project focused primarily on K-Means clustering and cluster evaluation.

📊 Dataset

The Breast Cancer Wisconsin (Diagnostic) dataset was used.

The numerical features were selected for clustering.

The target label was not used as an input to the clustering algorithm.

This allowed the clustering process to identify patterns based only on similarities among numerical features.

⚙️ Data Preparation

Before clustering, numerical features were standardized.

This was important because K-Means is distance-based and features with larger numerical scales could otherwise have a greater influence on cluster formation.

🔵 K-Means Clustering

K-Means clustering was applied using different candidate values of k.

The tested values included:

k = 2
k = 3
k = 4
k = 5
k = 6

Each configuration was evaluated using the Silhouette Score.

📏 Silhouette Score

The silhouette score measures how well observations fit within their assigned clusters compared with observations in other clusters.

The best tested configuration was:

Best tested k = 2

Silhouette Score ≈ 0.3434
📉 PCA Visualization

Principal Component Analysis (PCA) was used to reduce the standardized feature space to two dimensions for visualization.

The resulting two-dimensional representation allowed the clusters to be visually inspected.

PCA was used for dimensionality reduction and visualization.

🔬 Interpretation

The clustering analysis demonstrated that unsupervised learning can identify groups based on feature similarity without directly using predefined target labels.

The analysis also demonstrated the importance of evaluating different cluster configurations rather than selecting a value of k arbitrarily.

📚 Key Learning

Week 3 provided practical experience with:

Unsupervised learning
K-Means clustering
Feature standardization
Silhouette score
PCA
Cluster visualization
Interpretation of unsupervised patterns
🟢 Week 4 – Supervised Learning Model Implementation
🎯 Objective

The objective of Week 4 was to build and evaluate a supervised machine-learning model for a binary classification problem.

Unlike Week 3, the target labels were used during model training.

📊 Dataset

The Breast Cancer Wisconsin (Diagnostic) dataset was used for binary classification.

The task was to predict the target class using the numerical diagnostic features.

🤖 Model Selection

Logistic Regression was selected as the primary supervised-learning model.

Logistic Regression is suitable for binary classification and provides an interpretable baseline.

🔄 Workflow
Dataset
   ↓
Data Preparation
   ↓
Train/Test Split
   ↓
Feature Scaling
   ↓
Logistic Regression
   ↓
Prediction
   ↓
Evaluation
✂️ Train/Test Split

The dataset was divided into:

80% training data
20% testing data

A stratified split was used to maintain class proportions between training and testing datasets.

⚙️ Feature Scaling

StandardScaler was used to standardize numerical features.

The scaler was fitted on the training data and then applied to the test data.

This helps prevent information from the test set influencing preprocessing.

📊 Model Evaluation

The model was evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion matrix
Cross-validation

Results:

Test Accuracy ≈ 98.25%

5-Fold Cross-Validation Accuracy ≈ 97.80%
🧪 Cross-Validation

Five-fold cross-validation was used to examine model performance across multiple training and validation partitions.

This provides a more robust estimate of model performance than relying only on one train-test split.

📚 Key Learning

Week 4 provided practical experience with:

Supervised learning
Binary classification
Logistic Regression
Train-test splitting
Feature scaling
Cross-validation
Classification metrics
Confusion matrices
Model performance analysis
🔴 Week 5 – Deep Learning Application in Data Science
🎯 Objective

The objective of Week 5 was to explore the fundamentals of deep learning and implement a neural-network model using a popular deep-learning framework.

The project focused on designing, training, and evaluating a neural network for image-based classification.

📊 Dataset

The Scikit-learn Digits dataset was selected.

The dataset contains:

1,797 samples
64 pixel features
10 digit classes

The target classes represent:

0, 1, 2, 3, 4, 5, 6, 7, 8, 9
🧠 Problem Definition

The task was defined as a 10-class classification problem.

Given the pixel values of a handwritten digit image, the neural network predicts which digit from 0 to 9 the image represents.

🔧 Framework

PyTorch was used to build and train the neural network.

🏗️ Neural Network Architecture
64 Input Features
        ↓
128 Neurons + ReLU
        ↓
Dropout 0.20
        ↓
64 Neurons + ReLU
        ↓
Dropout 0.20
        ↓
10 Output Classes
⚙️ Design Decisions
ReLU Activation

ReLU was used in the hidden layers to introduce non-linearity.

Dropout

A dropout rate of 0.20 was used as a regularization technique to reduce overfitting risk.

Output Layer

The final layer contains 10 outputs corresponding to the ten digit classes.

Loss Function

Cross-entropy loss was selected for the multi-class classification problem.

Optimizer

The Adam optimizer was used for adaptive gradient-based optimization.

⚙️ Hyperparameters
Learning Rate: 0.001
Batch Size: 32
Epochs: 30
Dropout: 0.20
Optimizer: Adam
Loss: Cross-Entropy Loss
🏋️ Training

The model was trained using mini-batches.

During training:

Input data was passed through the neural network.
Predictions were generated.
Loss was calculated.
Backpropagation calculated gradients.
The optimizer updated model parameters.
Training and test performance were monitored.
📊 Evaluation

The model was evaluated using:

Accuracy
Weighted Precision
Weighted Recall
Weighted F1-score
Confusion matrix

Results:

Test Accuracy ≈ 98.06%

Weighted F1-score ≈ 0.9807
⚠️ Challenges

The main architectural limitation was that the 8×8 image data was flattened into 64 numerical features.

Because the spatial structure of the image was not explicitly preserved, the fully connected network cannot exploit local image patterns as efficiently as a CNN.

Other challenges included:

Overfitting risk
CPU-based training
Hyperparameter selection
Stable optimization
Appropriate model evaluation
🚀 Future Improvements

Potential improvements include:

Convolutional Neural Networks
Hyperparameter tuning
Early stopping
Learning-rate scheduling
Data augmentation
Larger image datasets
Transfer learning
📚 Key Learning

Week 5 provided practical experience with:

Neural networks
PyTorch
Deep-learning architecture design
Activation functions
Dropout
Backpropagation
Optimization
Model training
Deep-learning evaluation
Overfitting analysis
🟣 Week 6 – Integrative Capstone Project and Evaluation
🎯 Objective

Week 6 was the final and most comprehensive project of the internship.

The objective was to combine the major concepts learned throughout the previous five weeks into a complete Data Science pipeline.

The project included:

Data acquisition
Data cleaning
Preprocessing
Exploratory Data Analysis
Unsupervised learning
Supervised learning
Deep learning
Evaluation
Insights
Recommendations
Reflection
🩺 Capstone Project
Breast Cancer Classification and Patient Pattern Analysis

The project used the Breast Cancer Wisconsin (Diagnostic) dataset.

The dataset contains:

569 observations
30 numerical features
Binary target
🔄 Complete Data Science Pipeline
Data Acquisition
        ↓
Data Inspection
        ↓
Data Cleaning
        ↓
Data Preprocessing
        ↓
Exploratory Data Analysis
        ↓
K-Means Clustering
        ↓
Logistic Regression
        ↓
PyTorch Neural Network
        ↓
Model Evaluation
        ↓
Insights
        ↓
Recommendations
🧹 Data Cleaning

The capstone began with data-quality checks.

The following were examined:

Missing values
Duplicate records
Data types
Numerical feature distributions
Potential outliers

The IQR method was used to identify potential outlier values.

📊 Exploratory Data Analysis

EDA was performed to understand the dataset before modeling.

The analysis included:

Dataset dimensions
Descriptive statistics
Target-class distribution
Feature analysis
Correlation analysis
Visualization

EDA helped establish an understanding of the dataset before applying clustering and predictive models.

🔵 Unsupervised Learning

K-Means clustering was applied to standardized numerical features.

The target variable was not used during clustering.

Different values of k were tested.

The best tested configuration was:

k = 2

Silhouette Score ≈ 0.3434

PCA was used to visualize the cluster structure in two dimensions.

This stage demonstrated how unsupervised learning can identify patterns without relying on predefined labels.

🟢 Supervised Learning

Logistic Regression was implemented as the supervised-learning baseline.

The dataset was divided using an 80:20 stratified train-test split.

Feature scaling was performed using StandardScaler.

Results:

Accuracy ≈ 98.25%

Weighted F1-score ≈ 0.9825

The model was evaluated using:

Accuracy
Precision
Recall
F1-score
Confusion matrix
🔴 Deep Learning

A PyTorch Multilayer Perceptron was also implemented.

Architecture:

30 Input Features
        ↓
64 Neurons
        ↓
ReLU
        ↓
Dropout
        ↓
32 Neurons
        ↓
ReLU
        ↓
Dropout
        ↓
2 Output Classes

Results:

Accuracy ≈ 96.49%

Weighted F1-score ≈ 0.9651

The deep-learning component demonstrated how neural networks can be integrated into a broader Data Science pipeline.

📊 Capstone Model Comparison
Model	Accuracy	Weighted F1
Logistic Regression	≈98.25%	≈0.9825
PyTorch MLP	≈96.49%	≈0.9651

The comparison demonstrates that increased model complexity does not automatically guarantee better performance on every dataset.

A simpler model can perform strongly depending on the characteristics of the dataset and the problem.

⚠️ Capstone Challenges
Feature Scaling

Different features can have different numerical ranges, so standardization was used before clustering and neural-network training.

Data Leakage

For supervised and deep-learning models, preprocessing was fitted using training data before being applied to the test data.

Outliers

Potential outliers were investigated using the IQR method.

Cluster Selection

Multiple values of k were tested using the silhouette score.

Model Complexity

Logistic Regression was used as an interpretable baseline before introducing a more complex neural network.

Computational Resources

The dataset was compact enough to support CPU-based experimentation.

💡 Capstone Insights

The capstone demonstrated that different Data Science techniques serve different purposes.

Exploratory Data Analysis

Helps understand the dataset and identify patterns.

Unsupervised Learning

Discovers groups or structures without using target labels.

Supervised Learning

Uses labeled data to make predictions.

Deep Learning

Provides flexible non-linear modeling through neural networks.

Evaluation

Provides evidence about model performance and areas for improvement.

🚀 Future Work

Possible improvements include:

Hyperparameter tuning
Feature selection
Repeated cross-validation
Hierarchical clustering
DBSCAN
Ensemble models
Neural-network architecture optimization
Early stopping
Learning-rate scheduling
Probability calibration
Model interpretability
Advanced dimensionality-reduction techniques

For any real-world diagnostic application, additional domain validation and appropriate professional oversight would be required.

📚 Overall Learning Outcomes

After completing the six-week internship, I gained practical experience in the complete Data Science lifecycle.

Data Handling
Dataset acquisition
Data inspection
Data cleaning
Missing-value analysis
Duplicate detection
Outlier analysis
Feature scaling
Data Analysis
Descriptive statistics
Exploratory Data Analysis
Correlation analysis
Data visualization
Pattern identification
Machine Learning
K-Means clustering
Silhouette analysis
Logistic Regression
Train-test splitting
Cross-validation
Classification metrics
Deep Learning
PyTorch
Neural-network architecture
ReLU activation
Dropout
Backpropagation
Adam optimization
Cross-entropy loss
Evaluation
Accuracy
Precision
Recall
F1-score
Confusion matrix
Silhouette score
Training/test performance analysis
Documentation
Jupyter notebooks
Word reports
Technical explanations
GitHub organization
Project documentation
🛠️ Technologies Used
Programming
Python
Data Processing
NumPy
pandas
Visualization
Matplotlib
Seaborn
Machine Learning
Scikit-learn
Deep Learning
PyTorch
Development
Jupyter Notebook
Python
Documentation
Microsoft Word
Markdown
GitHub
📊 Project Summary
Week	Project	Main Techniques
Week 1	Data Cleaning & Preprocessing	pandas, NumPy, IQR, StandardScaler
Week 2	EDA & Visualization	pandas, Matplotlib, Seaborn
Week 3	Unsupervised Learning	K-Means, Silhouette Score, PCA
Week 4	Supervised Learning	Logistic Regression, Cross-validation
Week 5	Deep Learning	PyTorch, MLP, Dropout
Week 6	Integrative Capstone	EDA, K-Means, Logistic Regression, PyTorch
📈 Internship Progression

The internship followed a progressive learning structure:

WEEK 1
Data Cleaning & Preprocessing
        ↓
WEEK 2
Exploratory Data Analysis
        ↓
WEEK 3
Unsupervised Learning
        ↓
WEEK 4
Supervised Learning
        ↓
WEEK 5
Deep Learning
        ↓
WEEK 6
Integrative Capstone

Each week built upon the knowledge gained from the previous stages and gradually developed a complete understanding of the Data Science workflow.

📁 Deliverables

Each weekly project contains three main deliverables.

📄 Word Report

Contains:

Objective
Problem statement
Methodology
Implementation
Results
Analysis
Challenges
Conclusion
📓 Jupyter Notebook

Contains:

Python code
Data processing
Analysis
Visualizations
Model implementation
Evaluation
📊 Dataset

Contains the dataset used for the corresponding project.

🎯 Conclusion

The six-week YuvaIntern internship provided a structured and practical journey through Data Science with Python.

The projects progressed from basic data handling and preprocessing to exploratory analysis, unsupervised learning, supervised machine learning, deep learning, and finally a comprehensive capstone project.

The internship strengthened practical skills in:

Python programming
Data analysis
Data visualization
Machine learning
Deep learning
Model evaluation
Technical documentation
End-to-end Data Science workflows

The overall experience provided a strong foundation for applying Data Science techniques to structured datasets and developing complete analytical and machine-learning projects.

⭐ Acknowledgement

I would like to thank YuvaIntern for providing the opportunity to work on practical Data Science projects involving Python, machine learning, and deep learning.

The internship provided valuable hands-on experience in implementing, evaluating, documenting, and organizing Data Science projects.
