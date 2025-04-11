# NPRI-Pollutant-Prediction
The objective of this project is create a machine learning model that will reasonably predict the amount of ammonia, nitrate ions, and phosphorus released to water from wastewater treatment plants (in Canadian provinces) in 2023, using historical data from the National Pollutant Release Inventory (NPRI) (2000–2022) and relevant external data such as provincial population trends

**Project Overview**

This project is part of a series designed to give hands-on experience with real-world data exploration, cleaning, merging, and machine learning. Working in groups of up to 4 students, we use the National Pollutant Release Inventory (NPRI) dataset provided by Environment and Climate Change Canada to uncover patterns and predict key pollutant discharges into water.

Our primary task is to prepare and process historical data from 2000 to 2022 and predict the amount of ammonia, nitrate ions, and phosphorus released to water from wastewater treatment plants in 2023, based on provincial population trends.

**Dataset Description**

The NPRI data is divided into three core tables:
- Releases – Includes reported quantities of substances released directly to the environment.
- Disposals and Transfers – Tracks pollutants that are sent off-site for disposal or treatment.
- Comments – Supplementary information and context from facilities regarding reported data.

**Machine Learning Problem**

We framed this project as a time-series regression problem, focusing on predicting numeric outputs (pollutant quantities) based on both historical pollutant discharge data and external socio-environmental trends like provincial population growth.

**Project Phases**

Project 1: Exploratory Data Analysis (EDA)
- Investigated data quality, distribution, and structure
- Identified patterns, anomalies, and missing values
- Explored relationships between pollutants and geographic/population features

Project 2: Data Cleaning & Feature Engineering
- Handled missing values, outliers, and inconsistencies
- Merged the three NPRI tables to build a unified view
- Aligned external data (e.g., population statistics)
- Encoded features and engineered new attributes
- Created a machine-learning-ready dataset

Project 3: Model Preparation & Prediction
- Applied feature selection methods
- Trained time-series models for forecasting 2023 pollutant releases
- Validated predictions using cross-validation and historical backtesting
- Evaluated model performance using MSE, MAE, and R² metrics

**Tools & Technologies**

- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Google Collab Notebooks
- Matplotlib & Seaborn (for visualization)
- Prophet (for time-series modeling)
- Git/GitHub (for version control and collaboration)

**Learning Outcomes**

- Gain hands-on experience working with real-world environmental datasets
- Develop strong data exploration and cleaning skills
- Learn to handle time-series data and temporal patterns
- Understand the challenges of feature engineering and dataset merging
- Communicate effectively with stakeholders and document data processes
- Make informed machine learning decisions supported by domain knowledge


**Deliverables**

- A cleaned, aligned, and merged dataset ready for machine learning
- A fully trained model capable of predicting pollutant levels for 2023
- Documentation of data cleaning and modeling decisions
- Visualizations supporting our findings and predictions

**Contributors**

Abi Afolabi - aafolabi@norquest.ca

Abiola Bakare - abakare69@norquest.ca

Enkeshie Parris - eparris@NorQuest.ca

Ruth Olasupo - rolasupo@NorQuest.ca
