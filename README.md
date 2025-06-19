# H1B Visa Case Prediction (IS-734 Project)

This project analyzes and predicts the outcome of H1B visa applications using historical data sourced from Kaggle. The model aims to help identify key trends and factors that influence visa case certification.

## Objective
- Develop a machine learning model that classifies H1B visa applications as Certified or Denied.
- Extract insights into which features most impact decision outcomes.

## Dataset
- Source: Kaggle H1B Visa Dataset
- Records: ~50,000
- Duration: 2010–2020
- Key Features: Employer Name, Job Title, Full Time Position, Wage, Year, Worksite, Case Status

## Preprocessing Steps
- Handled missing values using forward fill and row dropping
- Removed redundant columns such as `Unnamed: 0`, `lon`, and `lat`
- Standardized and cleaned feature formats
- Reset DataFrame index after preprocessing

## Exploratory Data Analysis
- Top employers based on application volume
- Common job titles and worksite locations
- Wage distribution comparison across certified and denied cases

## Machine Learning Models (to be completed)
- Logistic Regression
- Random Forest / SVM (if included)
- Model evaluation using Accuracy and ROC-AUC metrics

## Visualizations
- Confusion Matrix
- ROC Curve
- Feature importance (if applicable)

## Key Insights
- Wage levels and job titles are major influencers of H1B case outcomes
- Certain employers and cities have higher certification probabilities

## Future Improvements
- Add more recent datasets
- Test ensemble models like XGBoost or LightGBM
- Apply model interpretability tools like SHAP for transparency

## Team Members
- Pranit Patil
- [Add additional names if applicable]

## License
This project is intended for academic and educational purposes only.
