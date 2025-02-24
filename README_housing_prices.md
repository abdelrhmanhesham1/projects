🏠 Housing Price Prediction
📌 Project Overview
This project focuses on predicting housing prices using Linear Regression and Polynomial Regression models. By analyzing various features such as area, number of bedrooms, bathrooms, and additional amenities, the model estimates house prices with high accuracy.

The project also includes data preprocessing, feature selection, and exploratory data analysis (EDA) to ensure a robust predictive model.

🛠️ Technologies Used
Python 🐍
Pandas & NumPy – Data preprocessing and feature engineering
Scikit-learn – Machine learning models (Linear & Polynomial Regression)
Matplotlib & Seaborn – Data visualization and correlation heatmaps
Plotly – Interactive visualizations for model performance analysis
⚙️ Features
✔ Data Cleaning & Preprocessing – Handling missing values, removing duplicates, and encoding categorical features.
✔ Exploratory Data Analysis (EDA) – Correlation heatmaps, boxplots, and summary statistics.
✔ Feature Engineering & Selection – Selecting the most relevant features based on correlation analysis.
✔ Model Training & Evaluation – Implementing:

Linear Regression (Custom & Scikit-learn)
Polynomial Regression (Degree = 2) for better accuracy
✔ Performance Metrics – Mean Squared Error (MSE) to evaluate model performance.
✔ Visualization of Predictions – Comparing models with scatter plots and regression curves.
📂 Dataset
The dataset contains housing attributes such as:
Price
Area
Number of bedrooms & bathrooms
Stories, parking, and other amenities
The target variable (price) represents the selling price of the house.
🚀 How to Run the Project
1️⃣ Install Dependencies
Make sure you have the required libraries installed:

bash
Copy
Edit
pip install pandas numpy seaborn matplotlib scikit-learn plotly
2️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/abdelrhmanhesham1/projects.git
cd projects
3️⃣ Run the Python Script
bash
Copy
Edit
python housing_price_prediction.py
The script will train the model and display prediction results, visualizations, and performance metrics.

📊 Model Performance
Model	Mean Squared Error (MSE)
Linear Regression (Scratch)	0.826
Linear Regression (Scikit-learn)	0.826
Polynomial Regression (Degree = 2)	0.793
🔹 Polynomial Regression provides better accuracy due to its ability to capture complex relationships in data.
