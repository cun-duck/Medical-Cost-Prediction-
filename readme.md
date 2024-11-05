# Medical Cost Prediction

## Project Overview
This project aims to predict medical insurance charges using patient data, applying Ridge Regression as the machine learning model. The dataset used includes features like age, BMI, sex, region, and whether the patient is a smoker. This analysis will help in identifying the factors influencing medical charges.

## Dataset
We use the **Medical Cost Personal Datasets** available from public sources. The dataset includes:
- **age**: Age of the patient
- **sex**: Gender of the patient
- **bmi**: Body Mass Index
- **children**: Number of children/dependents
- **smoker**: Whether the patient is a smoker
- **region**: Patient's residential area
- **charges**: Medical charges billed by health insurance

## Steps in This Notebook
1. **Data Loading and Exploration**: Load the dataset and understand its structure.
2. **Preprocessing**: Apply one-hot encoding to categorical features and standard scaling to numerical features.
3. **Model Training with Ridge Regression**: Train the Ridge Regression model and evaluate its performance.
4. **Evaluation**: Measure performance using Mean Squared Error (MSE) and R² Score.
5. **Visualization**: Plot predicted vs. actual charges for clear understanding of model accuracy.

## How to Run This Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/cun-duck/Medical-Cost-Prediction.git
