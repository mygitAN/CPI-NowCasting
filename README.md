CPI Nowcasting Project: README
Introduction
This project aims to nowcast the Consumer Price Index (CPI) and its sub-categories for three consecutive months using machine learning techniques. CPI is an important economic indicator that measures the average change over time in the prices paid by consumers for a basket of goods and services. Nowcasting CPI is crucial for banks, businesses, and policymakers to make informed decisions regarding interest rates, fiscal policies, and investment strategies.

This Python notebook contains the steps taken to preprocess the data, explore the features, develop and optimize the machine learning models, and evaluate their performance on nowcasting the next CPI values.

Project Overview
Data Preparation: The first step in the project is to gather and preprocess the data from various sources, such as historical CPI data, trade data, business confidence etc. Participants are encouraged to look for alternative data sources to improve their models.
Feature Engineering: In this step, we will explore the relationships between different features and the target variable (CPI). We will perform feature selection and transformation to create a feature set that is most relevant for our nowcasting task.
Model Development: We will experiment with different machine learning algorithms and neural network architectures to develop models that can accurately nowcast CPI values. We will also perform hyperparameter tuning and model optimization to improve the performance of our models.
Model Evaluation: We will evaluate the performance of our models using cross-validation and various evaluation metrics, such as Root Mean Squared Error (RMSE) which is strictly required for the project but also used R-squared (R²) score. We will select the best-performing model to nowcast CPI values for the given period.
Nowcasting: Finally, using the best-performing model, we will nowcast the next CPI value as well as CPI sub-categories for three consecutive months.
Goals
The main goal of this project is to develop a robust and accurate machine learning model for nowcasting the CPI and its sub-categories. The success of the project will be measured by the performance of the final model on predicting the next three months of CPI values.

We hope that this Python notebook will provide a clear understanding of the steps taken to achieve this goal and inspire others to explore the potential of machine learning and data science in the field of economics.

Setup and File Structure
All the files for this project are hosted on GitHub: https://github.com/mygitAN/CPI-NowCasting

Open the project in Google Colab, links are provided on the notebook. This will make things easy. You can clone the repository to your local machine if thats what you prefer.
Make sure you have all the required dependencies installed. For Google Colab, you don't need to worry about this step, as most of the dependencies are pre-installed.
Run the code in the provided order, starting from the data preparation step.
Environment
This project is developed and tested in Google Colab. It should also work on a local machine with similar specifications and the required dependencies installed.

For the environment, you can create a requirements.txt file with the following content:
