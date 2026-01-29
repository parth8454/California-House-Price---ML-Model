# California-House-Price---ML-Model

Welcome to my first machine learning project! In this repository, I have built a Random Forest Regression model to predict median house prices in California. 
By focusing heavily on Data Preprocessing and Feature Engineering, I was able to achieve a significant performance boost over the baseline model.

Key Results:
1) Random Forest $R^2$ Score: 0.8146 (81.4% variance explained)
2) Random Forest RMSE: $50,356.51
3) Baseline Comparison: Outperformed Linear Regression, which only achieved an $R^2$ of 0.676.

Instead of just fitting a model, I focused on making the data "model-ready":
1)Handling Outliers: Used IQR-based Capping to stabilize features like median_income and rooms_per_household, ensuring extreme values didn't skew the results.
2)Feature Engineering: Raw counts like total_rooms weren't enough. 

I engineered new ratios to capture density:
1) rooms_per_household (Average rooms per family)
2) bedrooms_per_room (Ratio of bedrooms to total rooms)
3) population_per_household (Average density per house)

Categorical Encoding: Handled ocean_proximity using One-Hot Encoding to maintain model compatibility.

FUTURE SCOPE:
1) Streamlit Integration: Working on a web app to make the model interactive for users.


