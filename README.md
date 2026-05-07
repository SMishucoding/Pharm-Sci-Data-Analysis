Pharmaceutical ML Analysis using Databricks and Spark
Overview
This project demonstrates a Spark-based pharmaceutical data analysis workflow originally developed in Databricks. The analysis creates and processes a 10,000-sample synthetic pharmaceutical dataset to explore how solubility and permeability may relate to drug absorption and compound behavior.
Objectives
Generate structured pharmaceutical sample data using PySpark
Categorize solubility, permeability, and absorption into interpretable groups
Apply clustering to identify patterns in drug property interactions
Build predictive models to estimate absorption using solubility and permeability
Evaluate model performance using RMSE
Dataset
The project uses a generated 10,000-record pharmaceutical dataset with the following variables:
`id`: unique sample identifier
`solubility`: simulated compound solubility value
`permeability`: simulated compound permeability value
`absorption`: simulated absorption value
category variables for solubility, permeability, and absorption
Methods
1. Data Generation and Cleaning
A PySpark workflow was used to create structured datasets for solubility, permeability, and absorption. The data was categorized into high and low groups to support interpretation.
2. Data Integration
The absorption dataset was joined with the solubility and permeability dataset using the `id` field to create a modeling-ready dataset.
3. Exploratory Data Analysis
Histograms were generated to examine the distributions of solubility and permeability.
4. Clustering
KMeans clustering was applied to identify natural groupings in the solubility-permeability feature space.
5. Predictive Modeling
Two regression models were trained and evaluated:
Linear Regression
Decision Tree Regression
Model performance was assessed using Root Mean Squared Error (RMSE).
Tools and Technologies
Databricks
Apache Spark / PySpark
Spark MLlib
Python
Matplotlib
Scikit-learn
Key Skills Demonstrated
Cloud-based analytics workflow
Spark data processing
Feature engineering
Machine learning model development
Model evaluation
Scientific data interpretation
Data visualization
Professional Framing
This project demonstrates how scalable analytics and machine learning can support pharmaceutical decision-making by identifying patterns in compound properties and estimating drug absorption behavior.
