# Earthquake Damage Predictor

This project presents a machine learning–based system designed to predict the structural damage level of buildings after an earthquake. 
The model classifies buildings into predefined damage grades using structural, environmental, and construction-related features. 
The objective is to support rapid post-disaster assessment, improve emergency response planning, and contribute to the scientific understanding of seismic vulnerability.

## Project Vision

The vision of this project is to integrate data-driven techniques into earthquake risk assessment. By analyzing structural attributes, geographical indicators, and material characteristics, the system aims to assist researchers, civil engineers, and disaster management authorities in evaluating building vulnerability. 
The model is built to be interpretable, scalable, and suitable for real-world decision-support applications.

## Objectives

### Primary Objectives
- Develop a machine learning classification model capable of predicting earthquake damage grades accurately.
- Identify influential structural and environmental factors that affect building vulnerability.
- Build a complete and reproducible ML workflow including preprocessing, modeling, evaluation, and interpretation.

### Secondary Objectives
- Support research in seismic risk assessment through data analysis and model insights.
- Provide performance metrics and visualizations that explain model behavior.
- Encourage the use of predictive analytics in disaster management and urban planning.

## Technical Overview

The project includes all steps of a standard ML pipeline: data preprocessing, exploratory analysis, feature engineering, model training, optimization, and evaluation.  
Key preprocessing tasks include handling missing values, encoding categorical variables, scaling numerical features, and identifying outliers.

Multiple algorithms were tested, including Random Forest, Gradient Boosting, XGBoost, Decision Trees, Logistic Regression, KNN, and SVM. Hyperparameter tuning was performed using grid search and cross-validation. 
Evaluation metrics include accuracy, precision, recall, F1-score, and confusion matrix analysis. Feature importance techniques were applied to determine which factors contributed most to the predictions.

## Features Used for Prediction

### Structural Features
- Number of floors  
- Age of building  
- Type of foundation  
- Type of roof  
- Construction materials  
- Ground floor area  
- Superstructure type  

### Environmental and Geographical Features
- Region identifier  
- Soil type or terrain characteristics  
- Local seismic intensity  
- Ground slope and environmental indicators  

### Usage and Infrastructure Features
- Building purpose (residential, commercial, industrial)  
- Construction quality indicators  

## Machine Learning Pipeline

The complete workflow of the project:
Data Acquisition → Cleaning → Feature Engineering → Model Selection → Training → Evaluation → Interpretation


## Key Insights

- Building material, age, and structural type have significant influence on predicted damage levels.  
- Geographical and environmental indicators also play a major role in vulnerability assessment.  
- Ensemble models such as Gradient Boosting and XGBoost produced the strongest predictive performance.  
- The model can assist in prioritizing rescue operations and identifying high-risk structures.

## Suggestions for Seismologists and Disaster Researchers

- Combine ML-based predictions with real-time seismic sensor outputs for improved accuracy.  
- Build region-specific models, as geological profiles vary significantly across locations.  
- Enhance datasets with more detailed structural parameters for deeper analysis.  
- Use satellite or drone imagery to validate predicted damage levels in real scenarios.  
- Collaborate with civil engineers to refine feature definitions and improve interpretability.

## Screenshots :

<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/867a456c-f510-4cec-8191-75d75bc1d7bc" />


<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/94f1c539-7656-4800-8f1d-fcc5fab2a835" />


<img width="1920" height="1080" alt="Screenshot (63)" src="https://github.com/user-attachments/assets/be58d72b-c632-4f41-9b64-3bd68d45aadf" />





