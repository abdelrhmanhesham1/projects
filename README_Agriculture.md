🌾**Crop Recommendation System**

**📌 Project Overview**

This project is an AI-powered crop recommendation system that helps farmers determine the best crop to grow based on soil and weather conditions. Using machine learning, the system predicts the most suitable crop based on factors such as soil nutrients (NPK), temperature, humidity, pH, and rainfall.

The project includes a Dash-powered interactive web application that allows users to input values using sliders and get real-time recommendations.

**🛠️ Technologies Used**

Pandas & NumPy – Data processing and manipulation

Scikit-learn – Machine learning model (Random Forest Classifier)

Dash & Plotly – Web dashboard for interactive crop recommendations

Dash Bootstrap Components – UI styling

Matplotlib & Seaborn – Data visualization

⚙️ Features

✔ Machine Learning Model – A trained Random Forest Classifier with 99% accuracy for crop prediction.

✔ Data Preprocessing – Handling missing values, feature scaling, and outlier detection.

✔ Dashboard Interface – Users can input soil and climate parameters through interactive sliders.

✔ Real-time Crop Recommendation – The system predicts and displays the best crop instantly.

✔ Model Evaluation – Includes accuracy metrics and a confusion matrix to assess performance.

📂 Dataset
The dataset contains 2200 samples with features such as Nitrogen (N), Phosphorus (P), Potassium (K), Temperature, Humidity, pH, and Rainfall.
The target variable (label) represents different crop types such as rice, maize, wheat, apple, banana, and more.

🚀 How to Run the Project

1️⃣ Install Dependencies

Make sure you have the required libraries installed:

pip install dash dash-bootstrap-components pandas scikit-learn matplotlib seaborn numpy

2️⃣ Clone the Repository

git clone https://github.com/abdelrhmanhesham1/projects.git

cd projects

3️⃣ Run the Crop Recommendation Dashboard

Execute the Python script to launch the web application:

python crop_recommendation.py

After running, open your browser and go to:

http://127.0.0.1:8050/

Now, you can use the interactive sliders to adjust values and get real-time crop recommendations!

📊 **Model Performance**

Accuracy: 99%

Classification Report:

Precision: 1.00 (for most crops)

Recall: 1.00 (for most crops)

F1-Score: 1.00 (for most crops)

cross validation: 0.97

🔥 Confusion Matrix

The model performs exceptionally well with high precision & recall across different crop types.

