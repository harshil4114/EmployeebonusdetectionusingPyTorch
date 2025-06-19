## Employee bonus detection using PyTorch

# Purpose of this project:
This project explores the use of a basic neural network model built with PyTorch to predict employee bonuses based on key performance indicators. The model is implemented in a Jupyter Notebook titled bonus_prediction_nn.ipynb, which contains all steps including data loading, preprocessing, model creation, training, and evaluation. By leveraging a simple feedforward neural network, this notebook demonstrates how machine learning can be applied to regression problems involving human resources or business analytics data.

# Project Exploration and Overview
The primary objective of this project is to predict the annual bonus for employees based on three input features: performance score, years of experience, and the number of projects completed. This predictive model can be a useful tool for HR departments to identify bonus structures that align with employee contributions and performance.
The model uses data from a CSV file named bonus.csv, which includes the following columns:
1. performance: A numerical indicator of the employee’s performance.
2. years_of_experience: The total number of years the employee has worked professionally.
3. projects_completed: The number of projects the employee has successfully delivered.
4. Bonus: The actual bonus amount received by the employee, used as the target variable for prediction.
The dataset is loaded using the pandas library, and then split into training and testing sets using scikit-learn's train_test_split function to evaluate model performance effectively.

# Methodology
The neural network is built using PyTorch's nn.Module and nn.Sequential interface. The architecture is intentionally simple, with a single linear layer that takes three input features and outputs one value (the predicted bonus). The purpose is to provide a foundation for understanding how neural networks work in the context of regression tasks.

# Technologies used
1. pandas: For data loading and manipulation.
2. scikit-learn: For splitting the dataset into training and testing subsets.
3. PyTorch: For building, training, and evaluating the neural network.
4. Jupyter Notebook: As the interactive coding environment.
