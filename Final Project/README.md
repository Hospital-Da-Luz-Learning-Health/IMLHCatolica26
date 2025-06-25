# Project assignment

You are expected to apply the knowledge acquired in this course in the form of a ML project that is due on the ??th July. In this project, you are expected to train a machine learning model that can predict a clinical outcome measure. The final deliverables are: 1) a report, 2) a presentation, 3) the code produced. This document introduces the dataset to explore and sets the outline of both the report and the presentation.


# Delivery Settings

There are two moments of delivery: 1) EDA and 2) Model development and validation pipeline.

## EDA
This phase consists of data analysis of the dataset. You are expected to submit **a single notebook** that contains a comprehensive analysis of this project's dataset. Feel free to use markdown cells for discussion of results, as well as plots and tables.

You have until **3rd July at 23:59** to submit this notebook.

## Model development and validation pipeline

In this phase you are expected to deliver **a single notebook** where you train and validate your ML models on the dataset , as well as provide your predictions to the `test set` in a csv file. 

> `submission tutorial.ipnb` explains how you can provide your predictions file.

You have until **10th July at 23:59** to submit your notebook and predictions file.


## The data set

The dataset includes over 4,240 records, with 15 attributes and a target. The goal of the dataset is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).

| **Column**          | **Description**                                                                 |
|---------------------|---------------------------------------------------------------------------------|
| **male**            | Gender of the patient (1 = male, 0 = female)                                   |
| **age**             | Age of the patient in years                                                    |
| **education**       | Education level of the patient (higher values represent higher education levels)|
| **currentSmoker**   | Whether the patient is a smoker (1 = current smoker, 0 = non-smoker)            |
| **cigsPerDay**      | Average number of cigarettes smoked per day                                     |
| **BPMeds**          | Whether the patient is on blood pressure medication (1 = yes, 0 = no)           |
| **prevalentStroke** | Whether the patient has a history of stroke (1 = yes, 0 = no)                   |
| **prevalentHyp**    | Whether the patient has a history of hypertension (1 = yes, 0 = no)             |
| **diabetes**        | Whether the patient has diabetes (1 = yes, 0 = no)                              |
| **totChol**         | Total cholesterol level in the blood (mg/dL)                                    |
| **sysBP**           | Systolic blood pressure (mmHg)                                                 |
| **diaBP**           | Diastolic blood pressure (mmHg)                                                |
| **BMI**             | Body Mass Index (kg/m²)                                                         |
| **heartRate**       | Heart rate (beats per minute)                                                  |
| **glucose**         | Glucose level in the blood (mg/dL)                                             |
| **TenYearCHD**       | Whether the patient developed CHD within the following 10 years                 |



## Machine Learning Prediction Project Outline

1. Introduction:
   1. **Objective**: Define the prediction task and the goal of the project.
   2. **Dataset Description**: Provide a brief description of the dataset, including the source and the type of data.
2. Exploratory Data Analysis:
   1. **Initial Exploration**: Perform basic statistics to understand the data.
   2. **Visualizations**: Remember to use tables and plots to help you communicate interesting patterns in data
   3. **Correlations**: Confirm and report if you have linearly dependent variables in the dataset
3. Model Training:
   1. **Data Splitting**: Split the dataset into training and testing sets.
   2. **Baseline Model**: Start with a simple model to establish a baseline performance.
   3. **Training**: Train multiple models on the training data.
   4. **Hyperparameter Tuning**: Use techniques like grid search or random search to optimize model parameters.
4. Model Evaluation
   1. **Metrics**: Choose appropriate evaluation metrics (e.g., accuracy, precision, recall, F1-score).
   2. **Validation**: Use cross-validation to assess model performance.
   3. **Model Comparison**: Compare the performance of different models.
5. Model Interpretation
   1. **Feature Importance**: Identify the most important features in the best-performing model.
   2. **Model Insights**: Provide insights based on the model's predictions.
6. Conclusion
   1. **Summary**: Summarize the key findings and results of the project.
   2. **Limitations**: Discuss any limitations encountered during the project.
   3. **Future Work**: Suggest possible improvements or next steps.
7. Documentation and Presentation
   1. **Report**: Prepare a comprehensive discussion in markdown cells of your notebooks.
   2. **Presentation**: Create a presentation to showcase the project findings.

## Tips for Students
1. **Reproducibility**: Ensure that all code and analyses can be reproduced by others.
2. **Clarity**: Write clear and concise code with comments.
3. **Visualization**: Use visualizations effectively to communicate insights.

