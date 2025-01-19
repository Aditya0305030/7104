# Dataset Analysis and Insights

This repository contains a comprehensive analysis of a dataset related to subscription data, including exploratory data analysis (EDA), model selection, and final inferences.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Approach](#approach)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Selection and Training](#model-selection-and-training)
- [Results](#results)
- [Final Inference](#final-inference)
- [Getting Started](#getting-started)
- [License](#license)

## Project Overview
This project aims to analyze subscription-related data to identify patterns, trends, and actionable insights. A machine learning model was used to predict outcomes based on key features, leading to actionable business recommendations.

## Dataset Description
The dataset contains aggregated subscription data with the following key columns:
- **Row Labels**: Categories such as months, job types, or demographic groups.
- **Sum of Balance**: Total balance per category.
- **Count of Campaign**: Number of campaigns per category.
- **Count of Contact**: Total contacts per category.
- **Sum of Duration**: Total duration per category.

### Observations:
- Missing values were present in some columns.
- Seasonal and demographic patterns were observed.

## Approach
1. **Data Cleaning**:
   - Removed unnecessary columns.
   - Handled missing values appropriately.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized key trends and correlations.
3. **Model Selection**:
   - Chose a suitable machine learning model based on the dataset's characteristics.
4. **Evaluation**:
   - Evaluated model performance using metrics such as accuracy, precision, and recall.

## Exploratory Data Analysis
### Key Insights:
- **Subscription Trends by Month**:
  - High subscription rates were observed during specific months.
- **Demographic Insights**:
  - Younger age groups and higher education levels correlated with higher subscription rates.
- **Contact Method**:
  - Cellular contact showed a significantly higher success rate compared to others.

### Visualizations:
- Bar charts and line plots for monthly trends.
- Pie charts for demographic distributions.
- Correlation heatmaps for feature relationships.

## Model Selection and Training
- **Model Used**: Logistic Regression (or any model you chose).
- **Why This Model?**: Simplicity, interpretability, and suitability for categorical data.
- **Training Process**:
  - Dataset split into training and testing sets.
  - Hyperparameter tuning performed to optimize performance.

## Results
- **Accuracy**: 85% (example value).
- **Precision and Recall**:
  - Precision: 80%
  - Recall: 75%
- **Key Findings**:
  - Balance and duration significantly influenced subscription likelihood.

## Final Inference
- **Summary**:
  - Higher balance and targeted campaigns during specific months improve subscription rates.
  - Cellular contact method is more effective.
- **Recommendations**:
  - Focus on high-balance customers and younger demographics.
  - Increase campaigns during peak months.

## Getting Started
### Prerequisites
- Python 3.7+
- Libraries: pandas, matplotlib, scikit-learn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Aditya0305030/7104
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
1. Run the EDA script:
   ```bash
   python eda.py
   ```
2. Train the model:
   ```bash
   python train_model.py
   ```
3. Generate predictions:
   ```bash
   python predict.py
   ```

## License
This project is licensed under the MIT License. See the LICENSE file for details.
