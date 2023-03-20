# Body-Weight-Prediction-Model
This is a machine learning project that aims to predict body weight in kilograms (kg) based on various health and fitness factors such as body fat percentage, calorie intake, and physical activity levels. The project uses a dataset of daily health and fitness metrics collected over three years by myself and using some apps to track my calories and my dayli steps, I manually added for years my workouts as well.


# Data
The dataset consists of a CSV file with 994 rows and 9 columns. the data came from a note file I had for several years, I have downloaded my Samsung health data for my step count and calories burnt data, Used MyFItnessPal for the calorie intake information, I have merged the data manually usimg an excel.
The columns are:

1. Day: the day of the week (string)
2. Date: the date of the measurement (string)
3. Workout: the type of workout performed (string)
4. Weight(Kg): the measured body weight in kg (float)
5. Bodyfat %: the measured body fat percentage (float)
6. Calorie_intake: the total calorie intake for the day (float)
7. Step_count: the total number of steps taken for the day (integer)
8. Distance_m: the total distance travelled in meters (float)
9. Calories_burnt: the total number of calories burned (float)

# Model
The project uses a Linear Regression model to predict body weight based on the other factors in the dataset. The model is trained on a randomly selected 70% of the data, and evaluated on the remaining 30% using mean squared error and R-squared metrics.

The Linear Regression model achieved the following performance metrics:

Mean squared error: 16.27
R-squared: 0.39
These metrics indicate that the model has moderate predictive power, but there is still room for improvement.

# Usage
To run the project, clone the repository and install the required packages. Then, run the predict_weight.py script to load the dataset, train the model, and make predictions on a randomly selected subset of the data.
