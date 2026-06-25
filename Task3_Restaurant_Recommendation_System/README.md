# Task 3: Restaurant Recommendation System

## Objective
Develop a content-based restaurant recommendation system that suggests restaurants based on user preferences such as cuisine type and price range.

## Dataset
The dataset contains restaurant information including:
- Restaurant Name
- Cuisines
- Price Range
- Location Details
- Cost Information
- Ratings and Votes

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## Methodology

### 1. Data Preprocessing
- Removed records with missing cuisine values.
- Selected relevant recommendation features.
- Combined cuisine and price range information.

### 2. Content-Based Filtering
- Applied TF-IDF Vectorization on recommendation features.
- Computed Cosine Similarity between restaurants.
- Recommended restaurants with the highest similarity scores.

### 3. Recommendation Criteria
- Cuisine Similarity
- Price Range Similarity

## Sample Recommendations

### Cafe Arabelle
Recommended similar Filipino restaurants with the same price range.

### Le Petit Souffle
Recommended similar French restaurants.

### Mad Mark's Creamery & Good Eats
Recommended similar Dessert and Ice Cream restaurants.

## Conclusion
The recommendation system successfully suggests restaurants that share similar cuisines and price ranges using content-based filtering techniques.