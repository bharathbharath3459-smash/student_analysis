# AI-Powered Student Performance Analysis and Prediction

## Project Overview

This project analyzes student academic performance using data analytics and machine learning techniques.

The project uses the UCI Student Performance dataset to identify patterns associated with students' final academic grades and develops machine-learning models to predict final performance.

The project includes data cleaning, exploratory data analysis, data visualization, feature encoding, machine-learning model development, model evaluation, feature importance analysis, and data-driven recommendations.

## Objectives

- Analyze student academic and behavioral information.
- Explore factors associated with final student grades.
- Perform data cleaning and exploratory data analysis.
- Identify important features using machine learning.
- Build models to predict final student performance.
- Compare different regression models.
- Provide data-driven recommendations for academic support.

## Dataset

**Dataset:** UCI Student Performance Dataset

**Dataset Source:**  
https://archive.ics.uci.edu/dataset/320/student+performance

For this project, the `student-mat.csv` dataset was used.

The dataset contains information about students' demographic background, family information, study habits, previous academic performance, absences, and final grades.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models

Two regression models were developed and evaluated:

1. Random Forest Regression
2. Linear Regression

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

## Model Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Random Forest Regression | 3.08 | 3.87 | 0.270 |
| Linear Regression | 3.40 | 4.20 | 0.141 |

Random Forest Regression performed better than Linear Regression on the test dataset because it achieved lower MAE and RMSE values and a higher R² score.

The Random Forest model was therefore selected as the better-performing model for this project.

## Key Findings

- The average final grade was approximately 10.42 out of 20.
- The median final grade was 11.
- The average number of absences was approximately 5.71.
- 83 students had at least one previous failure.
- 38 students had a final grade of 0.
- Feature importance analysis was performed using the Random Forest model.
- Random Forest performed better than Linear Regression on the test dataset.
- The Random Forest model achieved moderate predictive performance with an R² score of 0.270.

## Setup and Run Instructions

### 1. Install Python

Make sure Python 3.11 or a compatible Python version is installed on your system.

### 2. Download or clone the project

Download the project files and open the project folder in VS Code or another suitable development environment.

### 3. Install the required libraries

Open a terminal in the project folder and run:


pip install -r requirements.txt