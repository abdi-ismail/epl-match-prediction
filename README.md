# EPL Match Winner Prediction - Machine Learning Project

## Project Overview
This project aims to predict the winner of football matches in the English Premier League (EPL) using machine learning. By using historical match data and applying predictive modeling techniques, I will attempt to build a model that can forecast match outcomes.

I took on this project to improve my skills in data preprocessing, feature engineering, and predictive modeling using Python.

## Project Steps

1. **Importing Data from Kaggle**  
   - [Premier League Matches Dataset](https://www.kaggle.com/datasets/sajkazmi/premier-league-matches)  
   - [EPL 2023-2024 Season Matches](https://www.kaggle.com/datasets/mertbayraktar/english-premier-league-matches-20232024-season/data)

2. **Data Cleaning & Preprocessing**  
   - Handling missing values and inconsistent data.
   - Feature engineering using historical match results, team form, and match conditions.
   - Encoding categorical variables using pandas.

3. **Building the Prediction Model**  
   - Implementing machine learning models using scikit-learn.
   - Exploring different Random Forest classifiers 
   - Tuning to optimise model performance.

4. **Evaluating & Improving the Model**  
   - Measuring model accuracy and precision
   - Analysing prediction errors and refining feature selection.
   - Testing the model on new match data to assess generalisation.

## Results & Insights
- Initial predictions achieved an precision of **47%**, with improvements after feature selection and tuning.
- Certain features, such as team form (rolling averages of match statistics) and home advantage, had a significant impact on predictions.
- Managed to achieve a final precision of **63%** after optimising

## Future Improvements
- Experiment with different machine/deep learning models for improved accuracy.
- Deploy the model as a web app for interactive use.
- In the future I would like to extend the model to predict draws and losses separately, as currently it only predicts wins and not wins.
