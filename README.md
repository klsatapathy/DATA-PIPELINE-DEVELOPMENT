# DATA-PIPELINE-DEVELOPMENT

**COMPANY:-** CODTECH IT SOLUTIONS

**NAME:-** LOKANATH SATAPATHY

**INTERN ID:-** CT12WTOK

**DOMAIN:-** DATA SCIENCE

**DURATION:-** 12 NEEEKS

**MENTOR:-** NEELA SANTOSH


# Project Description: ETL Pipeline for Data Preprocessing, Transformation, and Loading

## Overview
This project implements an end-to-end ETL (Extract, Transform, Load) pipeline for data preprocessing and transformation using Python, Pandas, and scikit-learn. The pipeline is designed to handle common data preparation tasks required for machine learning workflows, including missing value imputation, categorical variable encoding, and feature scaling.

## Key Features

1. **Data Loading Flexibility**:
   - Supports both CSV and Excel file formats
   - Includes error handling for unsupported formats and file loading issues

2. **Comprehensive Preprocessing**:
   - Missing value detection and imputation (using mean for numerical columns)
   - Automatic one-hot encoding for categorical variables
   - Target column separation for supervised learning tasks

3. **Feature Scaling**:
   - Standardization of features using scikit-learn's StandardScaler
   - Preserves column names during transformation

4. **User-Friendly Interface**:
   - Interactive input for file path and target column selection
   - Clear output showing available columns and missing value statistics

5. **Output**:
   - Saves the processed dataset to a new CSV file ('cleaned_dataset.csv')
   - Maintains the relationship between features and target variable

## Technical Implementation

- **Languages/Libraries**: Python, Pandas, scikit-learn
- **Modular Design**: Separates concerns into distinct functions (loading, preprocessing, scaling)
- **Error Handling**: Includes try-catch blocks and input validation
- **Reproducibility**: Saves the complete processed dataset for future use

## Use Cases

This pipeline is particularly useful for:
- Preparing datasets for machine learning experiments
- Standardizing data preprocessing workflows across projects
- Teaching fundamental ETL concepts in data science
- Rapid prototyping of machine learning models

## Example Usage

The notebook demonstrates the pipeline using a diabetes dataset, showing how it:
1. Loads the raw data
2. Identifies and handles missing values
3. Transforms categorical data
4. Scales numerical features
5. Saves the processed output

The modular design allows for easy adaptation to different datasets and preprocessing requirements.
