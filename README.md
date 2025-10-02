# Tashkent-real-estate-ml
# Real Estate Price Prediction

## Project Description
This project focuses on predicting apartment prices in Tashkent using machine learning models.  
The goal is to analyze the housing dataset, engineer meaningful features, and build models to achieve accurate price predictions.

## Dataset
The dataset contains information about apartments, including:
- Size (m²)
- Price
- Number of rooms
- District
- Building characteristics (floor, total floors, elevator)

## Project Workflow
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering:
   - Log transformations (price, size, price per m²)
   - Binary flags (first floor, last floor, elevator, etc.)
   - Grouping rare room counts into "5+"
   - Average price per district
   - One-hot encoding for categorical variables
4. Model implementation:
   - Linear Regression (manual implementation via gradient descent)
   - Simple Decision Tree (manual)
   - Random Forest (sklearn)
5. Model evaluation and comparison  
6. Analysis of feature importance  
7. Conclusions

## Results
- Linear Regression explained the main price trends and achieved good accuracy.  
- Decision Tree (manual) illustrated simple rule-based splits.  
- Random Forest provided the best performance with R² ≈ 0.998 on the test set.  



