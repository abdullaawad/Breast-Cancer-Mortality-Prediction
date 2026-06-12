# Breast-Cancer-Mortality-Prediction

Breast Cancer Mortality Prediction — Machine Learning Classification

**Project Overview:**

This project applies machine learning to a critical real-world healthcare challenge: predicting breast cancer mortality and survival outcomes for patients. By building early screening models, the goal is to equip doctors with a data-driven tool to enhance treatment planning, prioritise care, and ultimately improve patient outcomes.

Breast cancer is the 2nd most common cause of cancer death in UK females, accounting for approximately 11,400 deaths per year (2017–2019). Early and accurate prediction of whether a patient will survive can meaningfully change the course of their care.


**Domain:**

Healthcare / Oncology — Breast Cancer Survival Prediction

Cancer occurs when cells in the body grow out of control. In breast cancer, abnormal cells form tumours that, if left untreated, can spread throughout the body and become fatal. Breast cancer cells typically originate inside the milk ducts and/or milk-producing lobules of the breast.

This project was commissioned by a team of doctors who provided historical patient records (including mortality status) and posed the following research question:


Does machine learning have the potential to assist doctors in predicting which patients will survive breast cancer?




**Objectives:**

As a Data Scientist embedded within a clinical team, the key objectives were to:


Analyse and preprocess a real-world breast cancer patient dataset
Build, evaluate, and compare multiple classification models for predicting mortality status (Survived / Did Not Survive)
Interpret and report findings in a way that is actionable for clinicians
Critically assess model performance to recommend the most suitable predictive tool



**Role & Responsibilities:**

Role: Data Scientist (working alongside a clinical team of doctors)

Key responsibilities included:


Performing exploratory data analysis (EDA) to understand the dataset and uncover patterns
Cleaning and preprocessing the data (handling missing values, encoding, scaling)
Engineering and selecting relevant features for model training
Building and tuning three machine learning classification models
Evaluating models using appropriate metrics and cross-validation
Communicating results clearly to a non-technical medical audience



**Skills & Technologies:**

CategoryTools / LibrariesLanguagePython 3Data Manipulationpandas, NumPyMachine Learningscikit-learn (sklearn)Data Visualisationmatplotlib, seabornModel Evaluationsklearn metrics (accuracy, precision, recall, F1, ROC-AUC, confusion matrix)EnvironmentJupyter Notebook


**Classification Models Built:**

Three classification models were implemented and compared:

1._ Logistic Regression (LR)_

A linear probabilistic classifier used as the baseline model. Logistic Regression estimates the probability that a patient belongs to a given mortality class, making it interpretable and well-suited for binary classification tasks in healthcare.

2. _K-Nearest Neighbours (KNN)_

A non-parametric, instance-based learning algorithm that classifies a patient based on the majority class of their K nearest neighbours in feature space. KNN is intuitive but sensitive to feature scaling and the choice of K.

3. _Naïve Bayes (NB)_

A probabilistic classifier based on Bayes' theorem, assuming conditional independence between features. Despite this strong assumption, Naïve Bayes often performs competitively on medical datasets and is computationally efficient.


**Evaluation Metrics:**

Each model was assessed using:


Accuracy — Overall correctness of predictions
Precision & Recall — Especially important in medical contexts to minimise false negatives (missed at-risk patients)
F1 Score — Harmonic mean of precision and recall
Confusion Matrix — Breakdown of true/false positives and negatives
ROC-AUC Score — Ability to discriminate between survival outcomes
