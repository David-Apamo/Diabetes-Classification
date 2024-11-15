# Diabetes-Classification
This repository contains files for Diabetes Prediction using Supervised Machine Learning, precisely Classification. The dataset used for analysis had various features like age, BMI, number of pregnancies, plasma glucose, diastolic blood pressure, triceps thickness, serum insulin, diabetes pedigree etc. The  data is a secondary dataset obtained online. [Link](https://raw.githubusercontent.com/MicrosoftDocs/ml-basics/master/data/diabetes.csv)

## Models Used:
* Logistic Regression
* Naive Bayes
* K-Nearest Neighbors (KNN)
* Random Forest (RF)
* XGBoost
* Artificial Neural Network (ANN)

After fine-tuning and evaluating the models, **XGBoost** achieved the best performance with an **Accuracy of 95.71%**. The model also had **93.2% Precision**, **Sensitivity(Recall) of 93.88%**, and a **ROC AUC** value of **0.99**.

## Key Processes:

* **Data Preprocessing:** Cleaning and normalizing data for improved model accuracy.
* **EDA:** Summarizing the data to obtain measures of centrality, and visualizing the data to understand existing patterns.
* **Model Training:** Training and fine-tuning various Classification models with cross-validation, and benchmarking the model training processes.
* **Model Evaluation:** Making predictions on test data that was set aside for model validation, and evaluating model performance using metrics like Accuracy, Recall/Sensitivity, Precision and ROC AUC.
* **Feature Importance Analysis:** Generating Feature Importance plot to obtain the important predictors of diabetes.

## Tools and Libraries

RStudio (tidyverse, janitor, caret, mlr, vip, pROC, parallel, parallelMap). Please install the specified packages prior to running the R markdown. The data is also large, so running the markdown will take about 2 to 3 hours. I've uploaded the knitted pdf version of the markdown file.

## Contributions

Contributions to improve the model performance and reliability are welcome. Please fork the repository, make your changes, and submit a pull request.
