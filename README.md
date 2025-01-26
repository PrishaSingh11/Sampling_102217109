# Sampling Techniques and Model Performance Evaluation

## Overview
This project evaluates the performance of various machine learning models on a dataset using different sampling techniques. The objective is to understand how different sampling methods impact the accuracy of machine learning models and to identify the best-performing combination.

## Dataset
The dataset used for this project is [Credit Card Data]. The dataset is highly imbalanced, and it is converted into a balanced class dataset using sampling techniques.

## Sampling Techniques
The following sampling techniques were used:
1. **Simple Random Sampling**: Selects a subset of individuals randomly from the larger dataset.
2. **Stratified Sampling**:Divides the population into homogeneous subgroups before sampling.
3. **Cluster Sampling**:Divides the population into clusters and randomly selects entire clusters.
4. **Bootstrap Sampling**:Selects a subset of individuals randomly with replacement from a larger dataset, allowing the same individual to be selected multiple times.
5. **Systematic Sampling**: Selects samples based on a fixed periodic interval.

## Machine Learning Models
The following machine learning models were evaluated:
1. **Random Forest**
2. **Logistic Regression**
3. **Support Vector Machine (SVM)**
4. **K-Nearest Neighbors (KNN)**
5. **Decision Tree**

## Requirements
This project is implemented in Python, using libraries such as Pandas, NumPy, scikit-learn, and imbalanced-learn. Ensure you have these installed:
```bash
pip install pandas numpy scikit-learn imbalanced-learn
```

 ## Setup and Execution
 1. Clone the repository or download the project to your local machine
 2. Place your dataset in the root directory or modify the dataset path in the script.
 3. Run the script using Python
``` bash
python sampling.py
```

## Project Workflow
1. **Data Preprocessing**:
   - Handle missing values, if any.
   - Normalize or standardize the data for models like SVM and KNN.
   - Encode categorical features as required.
2. **Balancing the Dataset**:
   - Applied sampling techniques to create balanced datasets.
3. **Model Training and Evaluation**:
   - Split the dataset into training and testing sets.
   - Train models using each sampling technique.
   - Evaluate the models using accuracy as the performance metric.
4. **Result Analysis**:
   - Compare the accuracy of models across different sampling techniques.
   - Identify the best combination of model and sampling method.

## Results
Results are saved in a pivot table in the Results folder which includes all results and the best results.In all__results, each row represents a machine learning model and each column a sampling technique and in best_results, the  best combination of model and sampling method is shown.


