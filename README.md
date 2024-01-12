# Real Estate Price Predictor App using FLASK

Welcome to the Real Estate Price Predictor Dashboard! This web application leverages machine learning to predict housing prices based on key features such as property size, number of bedrooms, and number of bathrooms. Built with Flask, a lightweight Python web framework, the dashboard offers an intuitive and user-friendly interface for users to input property details and receive accurate price predictions.


A dataset for 1000 units has been randomly generated using Python. The dataset contains variables such as 'property_size' in square feet, 'number_of_bedrooms' and 'number_of_bathrooms' as integers. The 'price' variable serves as the target variable. The generated data is very similar to realistic data.

This project has 3 major parts:
1.	price_predictor_model.py - This contains code for our Machine Learning model to predict real estate prices.
2.	app.py - This contains Flask app that receives real estate details, computes the precited value based on our model and returns it.
3.	templates - This folder contains the HTML template to allow user to enter real estate details to displays the predicted house prices.

You can run the price_predictor_model.py which will store the Linear Regression algorithm.

Project Setup
```
Open the Command line or Terminal
```

Clone the repository
```
git clone https://github.com/ttariqaziz/real_estate_price_predict_app_Flask
```
Move to the folder
```
cd <folder name>
```
To open with jupyter notebook (or maually open using jupyter notebook app)
```
jupyter notebook
```
To open app, open VS Code and in the terminal type
```
app.py
```
Which will basically run your model and generate a host id for example: http://127.0.0.1:5000/. You can then directly paste this Id in your browser and you will be able to see fields to enter some values to predict the real estate prices.

<img src = "https://github.com/ttariqaziz/housing_price_prediction_app/blob/main/images/Dashboard.jpg">
<img src = "https://github.com/ttariqaziz/housing_price_prediction_app/blob/main/images/Dashboard1.jpg">
<img src = "https://github.com/ttariqaziz/housing_price_prediction_app/blob/main/images/terminal.jpg">

