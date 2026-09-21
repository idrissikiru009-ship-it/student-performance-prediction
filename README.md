# student-performance-prediction 

About the Project

This project is my attempt to build a machine learning model that predicts student performance from a set of student-related features.

I used a synthetic student performance dataset from Kaggle and worked through the machine learning process myself, starting from exploring the data and understanding the relationships between the variables to building and evaluating a Linear Regression model.

A major part of this project was not just getting predictions, but understanding what is happening behind the model and implementing the calculations myself using NumPy.

What I Wanted to Learn

Through this project, I wanted to understand:

1. How to explore and prepare a dataset for machine learning.
2. How Linear Regression works.
3. How a model learns its parameters.
4. How predictions are generated.
5. How Mean Squared Error and Root Mean Squared Error are calculated.
6. What R² actually tells us about a model.
7. How the model’s performance changes when evaluated on unseen data.

Dataset

The dataset is a synthetic student performance dataset obtained from Kaggle.

It contains information about different factors related to student performance, with Performance Index used as the target variable.

Since the dataset is synthetic, the results from this project should not be treated as conclusions about real world students.

Exploratory Data Analysis

I first explored the dataset to understand its structure and the relationships between the variables.

The exploratory analysis included examining the data, looking at feature distributions, studying correlations, and using visualizations to identify patterns.

Linear Regression

I implemented Linear Regression using Python and NumPy rather than relying on a machine learning library to perform the core calculations.

This allowed me to understand what is happening inside the model instead of treating Linear Regression as a black box.

The implementation involved concepts such as:

1. Model parameters
2. Predictions
3. Mean Squared Error
4. Gradient Descent
5. Updating model parameters
6. Evaluating prediction errors

Train Test Split

I divided the dataset into training and testing data.

80% of the data was used to train the model, while 20% was used to test its performance on data that was not used during training.

The current split is randomly generated, so the evaluation results can change between different runs.

Model Evaluation

I evaluated the model using Mean Squared Error, Root Mean Squared Error, and R².

The current RMSE obtained from the model is:
0.0133

The R² score is used to understand how much of the variation in student performance is explained by the model.

Because the train test split is currently random, the R² score can change between 0.9967-0.9999

Tools Used

Python

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

Git and GitHub

Project Status

This project is still a work in progress.

I plan to continue improving it as I learn more about machine learning. Some of the things I intend to explore include cross validation, feature engineering, other regression models, and comparing different models based on their performance.

Repository Structure

student-performance-prediction/
│
├── student_performance_prediction.ipynb
├── README.md
└── .gitignore

Author

Idris Sikiru

Electronics and Computer Engineering Student

This project is part of my journey into Machine Learning, Data Science, and Artificial Intelligence.
