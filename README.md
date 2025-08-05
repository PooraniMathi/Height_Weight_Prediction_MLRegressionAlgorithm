1. Objective
The objective of this project is to predict a person's weight based on their height using a simple linear regression model. This machine learning approach helps to understand and model the relationship between height and weight.
2. Dataset Description
The dataset used for this project consists of height and weight data. The features include:
- Height (in cm)
- Weight (in kg)
3. Libraries Used
The following Python libraries were used to build and evaluate the model:
- numpy
- pandas
- matplotlib
- scikit-learn
- warnings
4. Data Preprocessing
The dataset was loaded using pandas and split into independent (X = Height) and dependent (y = Weight) variables. A train-test split was performed to prepare the data for model training and evaluation.
5. Data Visualization
A scatter plot was created to visualize the relationship between height and weight. This helped confirm the linear nature of the data, making it suitable for linear regression.
6. Model Building
A Linear Regression model from scikit-learn was trained on the training data. The model learned the relationship between height and weight, then used this information to predict weights for the test data.
7. Model Evaluation
The model’s performance was evaluated using Mean Squared Error (MSE). A lower MSE indicates better predictive accuracy.
8. Conclusion
The Linear Regression model successfully predicted weight based on height with reasonable accuracy. 
