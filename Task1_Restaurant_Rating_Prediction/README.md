# Restaurant Rating Prediction

## Objective
Build a machine learning model to predict the aggregate rating of restaurants based on various features.

## Dataset
- Records: 9551
- Features: 21
- Missing Values: 9 in Cuisines column

## Data Preprocessing
- Removed missing values
- Encoded categorical variables
- Split data into training and testing sets

## Features Used
- Country Code
- City
- Cuisines
- Average Cost for two
- Currency
- Has Table booking
- Has Online delivery
- Is delivering now
- Switch to order menu
- Price range
- Votes

## Models Used
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Results

| Model | MSE | R² Score |
|---------|---------|---------|
| Linear Regression | 1.5242 | 0.3344 |
| Decision Tree Regressor | 0.1738 | 0.9241 |
| Random Forest Regressor | 0.0993 | 0.9566 |

## Conclusion
Random Forest Regressor achieved the best performance and was selected as the final model.