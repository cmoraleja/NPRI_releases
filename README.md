# NPRI_releases
Objective: To forecast which Canadian province will experience the most significant reduction in substance releases (air, water, and/or land) over the next five years using data from the National Pollutant Release Inventory (NPRI).

Phase 1: Classification Model Preparation:
Data Aggregation: Substance releases were grouped into air, land, and water categories.
Unit Conversion: Standardized all release measurements to ensure uniformity across the dataset.
Missing Value Handling: Applied KNN Imputer to address missing Longitude and Latitude values.
Outlier Detection: Identified and managed outliers using the Interquartile Range (IQR) method.
Classification Model Preparation: Prepared the dataset for machine learning classification models.

Phase 2: Regression Model Preparation:
Column Standardization: Standardized column names and added a source column for future dataset merging.
Feature Engineering: Developed a target variable representing the rate of change, and engineered features for relative years.
Encoding: Encoded categorical features for machine learning compatibility.
Normalization: Applied normalization techniques to numerical features.
