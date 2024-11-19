 # Exploring Factors of Violence in Nigeria and Predicting Escalation

This project investigates conflict-related fatalities in Nigeria using two datasets: **Nigeria_ACLED.csv** and **violence.csv**. The goal is to identify factors associated with high fatalities and build predictive models for violence escalation.

## Part I: Data Exploration  
The first part of this project explores the **Nigeria_ACLED.csv** dataset, focusing on the variable *‘ACLED Fatalities’*.  
- **Objective**: Identify factors most associated with high fatalities.  
- **Methodology**:  
  - Analyzed key variables such as event types, actors, geographic locations, and ACLED notes.  
  - Applied data cleaning, feature engineering (e.g., binning and categorization), and statistical analysis.  
  - Visualized trends and associations using clear, interpretable plots.  
- **Findings**: Key factors contributing to high fatalities were identified and discussed, providing insights into patterns of violence in Nigeria.

## Part II: Machine Learning  
The second part uses the **violence.csv** dataset to predict the *‘Class’* variable, which indicates violence escalation.  
- **Objective**: Build predictive models to classify violence escalation.  
- **Methodology**:  
  1. Selected an evaluation metric based on dataset characteristics and project goals.  
  2. Trained and evaluated two models:  
     - Logistic Regression  
     - Random Forest  
  3. Compared model performance to determine the best fit for the task.  
  4. Applied techniques to improve performance (e.g., feature selection, hyperparameter tuning).  
- **Results**: Performance of both models was evaluated and enhanced, with explanations of the methods used for improvement.

## Tools & Technologies  
- Python  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- Geo-spatial and NLP techniques (where applicable)
