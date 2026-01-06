Welcome to Card Transaction Fraud Analysis which is a machine learning–driven project designed to help students and early-career professionals understand how real-world financial fraud detection systems are built and evaluated. This repository demonstrates an end-to-end fraud detection pipeline using historical credit card transaction data, covering everything from data understanding and preprocessing to model training, evaluation, and result interpretation.

In this project, the dataset is first explored to understand transaction patterns, feature distributions, and class imbalance commonly present in fraud detection problems. 

Data cleaning steps include:
1.handling missing values
2.removing irrelevant features
3.scaling numerical attributes
4.preparing the dataset for machine learning models. 
5.Feature selection techniques are applied to identify the most impactful variables that help differentiate between legitimate and fraudulent transactions and Hennce ensuring improved model performance and interpretability.

The project applies multiple machine learning algorithms to classify transactions as fraudulent or non-fraudulent. Model training is followed by evaluation using industry-standard performance metrics such as precision, recall, F1-score, and ROC-AUC, with a strong focus on minimizing false negatives due to the critical nature of fraud detection. Visualizations are generated to analyze transaction behavior, compare model predictions, and clearly demonstrate performance differences between algorithms.

A virtual environment can be created using python kernel ,venv or conda.
But venv or conda is recommended to install and manage dependencies efficiently before running the notebooks. Each notebook explains the purpose of the code blocks, making the project easy to run, modify, and extend.

This repository serves as a hands-on learning resource and a practical portfolio project that demonstrates applied skills in Python, data preprocessing, exploratory data analysis, machine learning, and model evaluation. Recruiters and reviewers can clearly see how raw financial data is transformed into a working fraud detection system, highlighting problem-solving ability, analytical thinking, and practical implementation of machine learning concepts.

Contributions are welcome in the form of improved documentation, additional models, enhanced preprocessing techniques, or extended visual analysis. This project is inspired by real-world financial fraud challenges and leverages open-source datasets and machine learning libraries to provide an industry-relevant learning experience.
The Dataset used in the project is not included due to size limits.You can download it from: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
