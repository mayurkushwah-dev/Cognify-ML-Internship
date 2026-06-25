# Task 2: Cuisine Classification

## Objective

Develop a machine learning model to classify restaurants based on their cuisines using restaurant-related features.

## Dataset

The dataset contains information about restaurants, including:

* Country Code
* City
* Average Cost for Two
* Currency
* Online Delivery Availability
* Table Booking Availability
* Price Range
* Votes
* Cuisine Information

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Methodology

### 1. Data Preprocessing

* Handled missing values in the cuisine column.
* Created a new feature called **Primary Cuisine** by extracting the first cuisine from cuisine combinations.
* Encoded categorical variables using Label Encoding.
* Split the dataset into training and testing sets.

### 2. Model Training

Two classification algorithms were used:

* Logistic Regression
* Random Forest Classifier

### 3. Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 57.02%   |
| Random Forest       | 52.34%   |

Logistic Regression achieved the best performance and was selected as the final model.

## Challenges

* Class imbalance among cuisine categories.
* Similar characteristics across different cuisines.
* Limited predictive power of restaurant metadata for cuisine identification.

## Conclusion

The project successfully classified restaurant cuisines using machine learning techniques. Feature engineering through Primary Cuisine extraction significantly improved model performance compared to using full cuisine combinations.
