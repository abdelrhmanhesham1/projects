# Laptop Recommendation Dashboard

## Overview
This project is an AI-powered laptop recommendation system that suggests the best laptop based on user preferences, such as processor type, RAM, storage, battery life, and budget. The system uses a **Random Forest Classifier** trained on synthetic data to provide accurate recommendations.

## Features
- **Machine Learning Model:** Utilizes a Random Forest Classifier with **97% accuracy**.
- **Interactive Dashboard:** Built with **Dash** for real-time laptop recommendations.
- **Data Processing:** Generates realistic synthetic data with varying hardware specifications.
- **User-Friendly Interface:** Allows users to adjust sliders for different specifications and get instant recommendations.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - `pandas`, `numpy` (Data processing)
  - `scikit-learn` (Machine learning)
  - `dash`, `dash-bootstrap-components` (Web dashboard)

## How to Run the Project
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn dash dash-bootstrap-components
   ```
2. Run the Python script:
   ```bash
   python app.py
   ```
3. Open the browser and go to `http://127.0.0.1:8050/` to access the dashboard.

## Usage
- Adjust the sliders for processor, RAM, storage, battery, and budget.
- The recommended laptop will be displayed based on your inputs.

## Model Performance
- **Accuracy:** 97%
- **Algorithm Used:** Random Forest Classifier

## Future Improvements
- Integrate real-world laptop datasets.
- Deploy on cloud platforms like Heroku or AWS.
- Add more user-specific filtering options.

---
Developed with ❤️ for AI-powered tech recommendations!

