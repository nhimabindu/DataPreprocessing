# DataPreprocessing🏠 Ames Housing Data Preprocessing Pipeline
📌 Project Overview

This repository demonstrates a complete data preprocessing pipeline using the Ames Housing dataset.
The objective is to prepare raw data for further machine learning and analytics tasks by applying essential preprocessing techniques.

Each preprocessing step was implemented by a different group member, committed individually to GitHub to ensure clear contribution tracking and collaboration best practices.

📂 Dataset

Dataset Name: AmesHousing.csv

Description: Contains housing-related features (numerical and categorical) used for price prediction and analysis.

🧠 Preprocessing Tasks & Group Contributions
Hima Bindu Nagendra Gowda: Importing Data & Handling Missing Values

Task Description:

Loaded the dataset using Pandas

Cleaned column names by removing spaces

Identified numerical and categorical columns

Imputed missing values:

Numerical features: Median imputation

Categorical features: Mode imputation

Verified that no missing values remain

Techniques Used:

Pandas

NumPy

Median & Mode imputation

📌 This step ensures a clean and complete dataset for downstream processing.

👤 Rahul Shrikant Devagiri: Scaling Numerical Features

Task Description:

Applied Z-score Standardization to normalize numerical features

Applied Min–Max Normalization to scale values between 0 and 1

Created separate scaled copies of the dataset for comparison

Techniques Used:

StandardScaler

MinMaxScaler

scikit-learn

📌 Scaling ensures that features contribute equally to machine learning models.

👤 Nidhi Nagaraja Bhangi: Handling Noise in Data

Task Description:

Injected artificial Gaussian noise into the target variable

Applied rolling mean smoothing to reduce noise

Visualized noisy vs smoothed data using line plots

Techniques Used:

NumPy random noise

Rolling window smoothing

Matplotlib visualization

📌 This step demonstrates how noise can be managed in real-world datasets.

👤 Kandarp Kiritkumar Patel: Outlier Detection & Treatment

Task Description:

Selected a numerical feature related to living area

Computed Z-scores to identify outliers

Removed records with Z-score > 3

Reported number of detected outliers and remaining records

Techniques Used:

Z-score method

SciPy

Statistical filtering

📌 Outlier handling improves model robustness and accuracy.

Zhixiao Yang: Feature Selection

Task Description:

Performed correlation-based feature selection

Identified numerical features most correlated with the target variable

Visualized top correlated features using a bar chart

Techniques Used:

Correlation analysis

Pandas

Matplotlib

📌 Feature selection helps reduce dimensionality and improve model performance.