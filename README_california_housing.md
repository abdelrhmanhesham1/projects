**🏡 California Housing Price Analysis**

**📌 Project Overview** 

This project analyzes housing prices in California using exploratory data analysis (EDA), visualization, and correlation analysis. 

The dataset, obtained from Scikit-learn’s California Housing dataset, includes factors like median income, house age, average rooms, and population to understand their impact on house prices.

The project involves data preprocessing, statistical analysis, and geospatial visualization to uncover housing market trends.

🛠️ **Technologies Used**

Pandas & NumPy – Data manipulation and preprocessing

Matplotlib & Seaborn – Data visualization

Scikit-learn – Fetching dataset and performing correlations

Plotly – Interactive map visualizations

Missingno – Handling missing values

**⚙️ Features**

✔ Dataset Exploration – Checking for missing values, duplicates, and basic statistics.

✔ Outlier Detection – Identifying extreme values using boxplots and IQR method.

✔ Correlation Analysis – Finding relationships between variables and house prices.

✔ Scatter Plots & Regression Analysis – Visualizing feature importance.

✔ Geospatial Visualization – Using Plotly Mapbox to analyze housing price distribution across California.

📂 **Dataset Information**

The dataset consists of 20,640 rows and 9 features, where MedHouseVal (Median House Value) is the target variable.

*Feature	Description*

MedInc	Median income in the block group

HouseAge	Median house age

AveRooms	Average number of rooms per household

AveBedrms	Average number of bedrooms per household

Population	Total population in the block group

AveOccup	Average number of occupants per household

Latitude	Geographical latitude

Longitude	Geographical longitude

MedHouseVal	Median house value (target variable)

**📊 Key Insights**

🔹 Correlation Analysis

Income (MedInc) has the strongest positive correlation (0.69) with house prices.

Latitude & Longitude have negative correlations, indicating location-based price variations.

Average Bedrooms (AveBedrms) shows a weak negative correlation (-0.098), meaning more bedrooms don’t necessarily increase price.

**🔹 Geospatial Analysis**

The highest-priced homes are concentrated in coastal areas (near Los Angeles, San Francisco, and San Diego).

Older homes tend to have lower prices, while newer homes are more expensive.

High-income regions have higher median house values, confirming that income level significantly influences property prices.


