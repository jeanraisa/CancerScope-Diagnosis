# Cancer Diagnosis using Neural Networks

# Project Overview
This project aims to indicate  cancer diagnosis status using a  simple machine learning model without optimization and optmized model. Through machine learning techniques we aim to improve diagnostic accuracy in healthcare.

# Project Objectives
* Enhance Diagnostic Accuracy: use of  AI algorithms to analyze cancer-related patient data, identifying potential indicators of cancer with greater precision.
* Accelerate Diagnosis Process: reduce the time required for cancer diagnosis, enabling healthcare professionals to dedicate more time to patient care and treatment planning.
* Extract Data-Driven Insights
* Facilitate Early Detection

# About Dataset
Data has been collected from different hospitals and contains medical and lifestyle information for patients, and is balanced with respect to feature distributions and includes realistic variability in patient data.
* Age: patient's age, ranging from 20 to 80.
* GeneticRisk: representing genetic risk levels for cancer, with 0 indicating Low, 1 indicating Medium, and 2 indicating High.
* Smoking: indicating smoking status.
* AlcoholIntake: representing the number of alcohol units consumed per week.
* Diagnosis:  indicating the cancer diagnosis status, where 0 indicates No Cancer and 1 indicates Cancer.
* PhysicalActivity: representing the number of hours per week spent on physical activities, ranging from 0 to 10.

# Model Implementation
Two models were developed:
1. Simple Machine Learning Model(A basic neural network model  without any optimization techniques.):
   * Accuracy: 0.723
   * Loss: 0.590
   * Precision: 1.0000
  
2. Optimized Machine learning Model with L2 Regularization, Dropout, Batch Normalization, RMSprop Optimizer and Early Stopping techniques:
   * Accuracy: 0.876
   * Loss: 0.300
   * Precision: 0.8762 

# Instructions for running
* Clone this repository.
* Ensure you have Python installed along with necessary libraries (TensorFlow, NumPy, etc.).
* Run the notebook.ipynb file in any compatible environment and execute the cells to run the analysis.

# Conclusion
 The main goal  is to develop a machine learning model for  cancer detection , improving the accuracy and speed of diagnosis in the healthcare system.

