# OCD Handwash detection

This project is designed to classify Routine or Compulsive Handwashes to help OCD patients. The primary functionalities include counting rows in CSV files, combining them into a single DataFrame, processing and cleaning the data, creating sliding windows for time series classification, and training a Random Forest model for the binary classification

## Table of Contents

1. [Requirements](#requirements)
2. [Usage](#usage)
3. [Functions](#functions)
    - [count_rows_in_csv_files](#count_rows_in_csv_files)
    - [combine_csv_files](#combine_csv_files)
    - [Data Cleaning and Preparation](#data-cleaning-and-preparation)
    - [Time Series Windowing](#time-series-windowing)
    - [Random Forest Classification](#random-forest-classification)
4. [Results](#results)

## Requirements

Make sure you have the following libraries installed before running the code:
pip install pandas numpy matplotlib scikit-learn imbalanced-learn
## Usage

Set the folder path: Update the folder_path variable in the script to the path where your CSV files are stored.

## Functions
Functions Overview  
count_rows_in_csv_files: Counts the number of rows in each CSV file in a specified folder, excluding headers.  
combine_csv_files: Combines all CSV files in a specified folder into a single DataFrame.
Data Cleaning and Preparation: Cleans and preprocesses the data by dropping unwanted rows and selecting specific columns.  
Time Series Windowing: Creates sliding windows of data for time series classification.  
Random Forest Classification: Trains a Random Forest classifier on the prepared data and evaluates its performance.

## Results
The script prints the following metrics to evaluate the classifier's performance:
F1 Score
Precision
Recall
Confusion Matrix


