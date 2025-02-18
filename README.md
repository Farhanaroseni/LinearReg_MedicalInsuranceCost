## Executive Summary

A linear regression model was develop to predict annual medical insurance cost, using information such as age, sex, BMI, number of children, smoking habits and region of residence. The model was trained on historical actual annual medical charges data and evaluated for accuracy. Results indicate that the model can predict the annual medical insurance cost with an R-squared value of 0.80, suggesting a strong fit.

## Objective

The objective is to build a predictive model to estimate annual medical insurance cost based on available features.

## About Dataset

Data Sources : https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv

The dataset used for this project is a historical Medical Cost Data. Below is the list of the features in the dataset.

Columns:

- age: Age of primary beneficiary
- sex: Gender (female/male)
- bmi: Body mass index
- children: Number of dependents
- smoker: Smoking habits(smoker/non-smoker)
- region: The beneficiary's residential area in the US (northeast/southeast/southwest/northwest)
- charges: Individual medical costs billed by health insurance

## Workflow

1. Data Preparation
2. Exploratory Analysis
3. Model Training
4. Evaluate Model Performance

## Conclusion

The model that we get from Linear Regression provides a reliable Medical Insurance Cost with R-squared value of 0.80.

## Recommendations

- It is recommended to explore more features like family history, pre-existing conditions or income that might improve the model’s performance
- In the next work, we could try to explore other advanced models such as Random Forest or SGD and compare their performance and choose the best one.
