# [Machine Learning Engineer - Test Task (2024)](https://github.com/naumovakotya/My_projects_DS/blob/main/Mains_lab/MLE_NaumovaE.ipynb)

[Link to Task Description](https://incredible-tulip-5c3.notion.site/Machine-learning-engineer-2024-e4c30223002a4eebb33d2cdeb8f81fb1)

## Task Overview

The dataset consists of insured individuals under the voluntary medical insurance (VMI) program. The objective is to predict the number of medical visits in 2023 based on the insured's characteristics and their medical visit history from 2022.

### Available datasets:
- `train` – training and validation dataset, including 50,000 insured individuals with target values.
- `holdout` – final evaluation dataset with 10,000 insured individuals (target values are hidden).

**Target Metric**: Mean Squared Error (MSE)

## Project Plan
1. Load required libraries and datasets.
2. Conduct data analysis, including preprocessing (handling missing values, duplicates, and processing textual data) and exploratory data analysis (EDA).
3. Train multiple models and select the best performing one.
4. Test the best model on the holdout dataset.
5. Draw conclusions and generate reports.

## Project Specifications:
- **Random State**: 42
- **Test Size**: 20%
- **Metric**: MSE (Mean Squared Error)
- **Output**: Feature importance graph for the best model.

## Expected Outputs:
1. A Jupyter notebook or `.py` file containing:
   - Data preprocessing code.
   - Model training code.
   - Model evaluation code.
2. A `.csv` file with predictions for the `holdout` dataset (with insured IDs and model predictions).
3. A list of used features with their respective importance scores.
4. Detailed comments and insights throughout the notebook.
