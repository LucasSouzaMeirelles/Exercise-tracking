1.Summary: This project's goal was to develop a ML model to predict the amount of calories burned after a workout session based on features like age, weight, session duration and water intake.

2.Results: The final model (final_model.pkl) is a Gradient Boosting Regression model fit on the target variable "calories_burned" and several numeric and categorical variables. The final r-squared was close to 100%, and the normalized RMSE (RMSE/standard deviation of y) was below 0.1.

3.Approach:

3.1-DW: Data Wrangling

3.1.1-Input: gym_members_exercise_tracking.csv (raw data)

3.1.2-Output: wrangled_data.csv

3.2-EDA: Exploratory Data Analysis and Visualization

3.2.1-Input: wrangled_data.csv

3.2.2-Output: analyzed_data.csv

3.3-MDE: Model Development and Evaluation

3.3.1-Input: analyzed_data.csv

3.3.2-Output: final_model.pkl

3.4-Deliverable: A function to generate predictions based on the developed model.
