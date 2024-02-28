# Talent Hunting Classification with Machine Learning

## Project Overview

This project focuses on classifying talent hunting assessments using machine learning techniques. The dataset includes evaluations by scouts on various attributes of players, aiming to predict the potential label of each player (average, highlighted). The project involves data preprocessing, exploratory data analysis, feature engineering, and the development of a machine learning model.

## Dataset

The dataset consists of several variables, including:
- `task_response_id`: Identification of a scout's evaluations for a team's players in a match.
- `match_id`: ID of the relevant match.
- `evaluator_id`: ID of the evaluator (scout).
- `player_id`: ID of the player being evaluated.
- `position_id`: ID representing the player's position (1-10).
- `analysis_id`: Identification of evaluations for a player in a match by a scout.
- `attribute_id`: ID of each attribute being evaluated.
- `attribute_value`: Score assigned by the scout to a player's attribute.
- `potential_label`: Label indicating the scout's final decision about a player's potential.

## Project Steps

1. **Merge Dataframes:** Combine two CSV files using the `merge` function based on specific columns.
2. **Filter Positions:** Exclude goalkeepers (position_id: 1) from the dataset.
3. **Filter Labels:** Remove the "below_average" potential_label category.
4. **Create Pivot Table:** Generate a pivot table to manipulate the data, with each row representing a player.
5. **Numerical and Categorical Analysis:** Analyze numerical and categorical variables, exploring player positions and potential labels.
6. **Numerical Variable Analysis:** Investigate numerical variables' distribution and correlation with the target variable.
7. **Feature Extraction:** Generate new features based on numerical variables.
8. **Label Encoding:** Convert categorical variables ("potential_label" and "mentality") into numerical format.
9. **Standard Scaling:** Standardize numerical variables using StandardScaler.
10. **Machine Learning Model Development:** Implement various machine learning models and evaluate their performance.
11. **Hyperparameter Optimization:** Optimize hyperparameters for the selected machine learning model.
12. **Feature Importance:** Determine feature importance using the `feature_importance` function.


## Acknowledgments

- This project is part of the Miuul Data Scientist Bootcamp, where I gained valuable insights and hands-on experience in data science techniques and methodologies.
- Special thanks to Vahit Keskin, Furkan Akdağ, Elif Aykut, Selen Karadağ, Ayça Nur İşçioğlu, Ayşe Çakır  and fellow participants for their support and collaboration during the bootcamp.
