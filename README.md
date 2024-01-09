# NFL Big Data Bowl: Tackling Proficiency Prediction

## Overview

The NFL's Big Data Bowl for 2024 challenges participants to harness Next Gen Stats player tracking data to develop innovative metrics related to tackling proficiency in American football. The competition revolves around creating actionable insights by leveraging the vast dataset encompassing Weeks 1-9 of the 2022 NFL season. The provided data includes player locations, speed, acceleration, and additional statistics like Expected Points and Win Probability.

## Objective

This project aims to address the complexities of evaluating tackling proficiency in the NFL. Traditional box-score metrics tend to present biased and incomplete assessments due to volume bias, positional disparities, and the absence of situational context. To overcome these limitations, a predictive model is employed. It factors in contextual elements to estimate the likelihood of successfully completing a tackle against a pass catcher, refining defensive capability assessment.

## Methodology

**Data Insights:**
- Insights into tackle distributions across positions reveal patterns in tackling rates influenced by the number of players and opportunities.

**Feature Engineering:**
- Engineered key features such as blocker presence, positioning, speed differentials, angle, distance from sideline, weight, and defender height to enhance the model's predictive capacity.

**Model Evaluation:**
- Employed algorithms like Logistic Regression, Random Forest, Gradient Boosting, and XGBoost for tackle probability predictions.
- Prioritized precision and recall due to class imbalance, ultimately relying on the F1 Score to gauge model performance.

**Model Refinement:**
- Executed Random Search on hyperparameters to fine-tune the XGBoost model for better precision in predictions.

**Model Evaluation and Comparison:**
- Comprehensive model evaluation using ROC and precision-recall curves, feature importance analysis, and learning curve plots.
- Emphasized the model's ability to distinguish between successful and unsuccessful tackles (AUC-ROC: 0.93) and evaluated precision-recall trade-offs (AUC-PR: 0.7).

**Player Performance Analysis:**
- Conducted detailed analysis comparing top players within their positions based on tackles and tackle success ratio derived from predicted probabilities.

## Results

The predictive model exhibited robust capabilities in distinguishing between successful and unsuccessful tackles. Notably, the success ratio uncovered substantial variations in player tackling abilities, contrasting with conventional box score metrics. The analysis revealed nuances in player performance within positions, showcasing the model's efficacy in providing a more nuanced view of tackling proficiency.
