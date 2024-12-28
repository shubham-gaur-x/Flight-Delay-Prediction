
# Flight Delay Prediction: Data Mining Project

## Overview
Flight delays pose significant challenges for the aviation industry, causing inconvenience to travelers and financial losses to airlines. 
This project applies various data mining techniques to predict flight delays and classify airline types, leveraging machine learning models.

## Objective
1. Improve understanding of factors influencing flight delays and airline characteristics.
2. Implement and evaluate multiple machine learning models for regression (predicting delay duration) and classification tasks.
3. Compare the performance of models and provide actionable insights.

---

## Dataset
- **Source**: [Flights Dataset on Figshare](https://figshare.com/articles/dataset/flights_csv/9820139)
- **Size**: Over 105,000 rows and 30 features after cleaning null entries.
- **Features**: Includes time-related data, airline identifiers, departure/arrival times, and delay information.

### Data Cleaning
- Removed columns with missing or irrelevant data such as `DIVERTED` and `CANCELLED`.
- Cleaned null entries, reducing the dataset to 105,000 records while maintaining data integrity.

---

## Exploratory Data Analysis (EDA)
1. **Correlation Analysis**: Identified significant relationships between variables like `SCHEDULED_DEPARTURE` and other time-related features.
2. **Delay Insights**: Examined top airports by arrival and departure delays.

---

## Machine Learning Models
### 1. Linear Regression
- **Purpose**: Predict flight delay durations using numeric features.
- **Insights**: Identifies linear relationships between delays and factors like departure times and distance.

### 2. Random Forest
- **Purpose**: Model complex, non-linear relationships for predicting departure delays.
- **Insights**: Provides feature importance and aids in mitigation strategies.

### 3. Gradient Boosting Machines (XGBoost)
- **Purpose**: Perform regression and classification tasks for delay predictions.
- **Insights**: Offers high predictive accuracy and models intricate relationships.

### 4. Neural Networks
- **Purpose**: Capture complex non-linear patterns influencing delays.
- **Insights**: Provides superior performance but may be less interpretable.

### 5. Decision Tree Regression
- **Purpose**: Model non-linear relationships between flight attributes and delays.
- **Insights**: Reveals delay-causing patterns, though interpretation may be challenging.

---

## Model Performance
- Neural networks achieved the highest performance with near-perfect accuracy, capturing intricate data patterns effectively.
- Considered overfitting by comparing training and testing scores to ensure reliability.

---

## Hyperparameter Tuning
- Employed techniques like grid search and cross-validation to optimize model performance.

---

## Conclusion
This project demonstrates the potential of machine learning to predict flight delays and identify critical factors causing delays. Neural networks outperformed other models, highlighting their ability to capture complex data patterns.

---

## Team
- **Shubham Gaur**
- **Malhar Ghogare**

## License
This project is for academic purposes and is not licensed for commercial use.

## Acknowledgments
Special thanks to [Figshare](https://figshare.com/) for providing the dataset.
