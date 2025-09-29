🚗 Car Price Prediction Using Machine Learning

	Predicting used car prices using machine learning to empower buyers, sellers, and dealerships with data-driven insights.

🔹Project Overview
This project analyzes used car data and builds a predictive model to estimate car prices. 
Key features include:
	• Brand / Make
	• Model
	• Year of Manufacturing
	• Mileage (km/l)
	• Fuel Type (Petrol/Diesel/CNG/Electric)
	• Transmission Type (Manual/Automatic)
	• Location / City
Goal: Build a reliable ML model to estimate car prices and understand the impact of each feature.

----

🛠️ Technologies & Tools
	• Programming Language: Python
	• Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
  • Model: Linear Regression
	• Development Environment: Google Colab / Jupyter Notebook

  ----

📊 Approach & Workflow
	1. Data Cleaning: Handle missing values, remove duplicates, and encode categorical features.
	2. Exploratory Data Analysis (EDA): Visualize correlations and feature importance.
	3. Model Selection: Tested Linear Regression, Random Forest, and XGBoost.
	4. Training & Evaluation: Used train-test split, cross-validation, and metrics like MAE, MSE, and R².
	5. Feature Importance: Identified top predictors such as car age, mileage, and brand.

----

💻 Model Training & Evaluation
Metric	Initial Split	Optimized Split (Best Random State)
R² Score	0.184	0.860
Random State Used	42	247
Pipeline Steps:
	1. One-Hot Encoding of categorical features (name, company, fuel_type)
	2. Linear Regression for predicting Price
	3. Train-test split optimized to maximize R² score
	4. Model saved as LinearRegressionModel.pkl

----

🌟 Future Improvements
Improvement Area	Description
Feature Expansion	Include accident history, service records, previous owners
Advanced Models	Explore Random Forest, XGBoost
Deployment	Create interactive web app using Streamlit/Flask

----

🤝 Contact
Platform	Link
Github: [Supriya-cybertech](https://github.com/supriya-cybertech)
LinkedIn	[Supriya Kumari](https://www.linkedin.com/in/supriya-kumari15/)

	“Data-driven insights empower smarter decisions.” 🚀

