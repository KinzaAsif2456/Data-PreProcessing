# Data-PreProcessing
This repository contains a collection of data preprocessing scripts, tools, and techniques used to clean, transform, and prepare datasets for analysis and modeling

##What's Inside
**Scripts**: A folder containing Python scripts for data cleaning, including:
1)Handling missing values
2)Handling duplicates
3)Handling inconsistent data
**Tools**: A folder containing pre-built tools and libraries for data cleaning, including:
1)numpy 
2)skit_learn
3)pandas
**Techniques**: A folder containing documentation and examples of various data cleaning techniques, including:
1)Data loading 
2) Data Cleaning
3) Displaying Data
4) Feature Scaling
4) Training and splitting data for model creation
**Datasets:**
A folder containing sample datasets used for testing and demonstrating data cleaning techniques.

## Introduction
This project uses the annual_temp_gcag.csv dataset to predict temperature trends. It applies several regression techniques to assess and compare their performance.
**Data Loading**
The dataset is loaded from the path /content/annual_temp_gcag.csv. It includes the columns Year and Temperature(Mean)

## Data Preprocessing

**Data preprocessing involves:**
1)Filling missing values
2)Splitting data into features and target variable
3)Splitting into training and testing sets

**Splitting Data set**
plit datasets into training and testing subsets using the train_test_split function from the sklearn.model_selection module. The purpose of this operation is to prepare data for machine learning model training and evaluation.



## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
This repository was inspired by the work of [Kinza Asif] and the Google Colab notebook Data Cleaning Notebook.

## Contact
If you have any questions or need help with this repository, please don't hesitate to reach out to [Kinza Asif] at [sweetykinzy2@gmail.com].
