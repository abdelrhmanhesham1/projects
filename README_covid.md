**🦠 COVID-19 Dashboard**

**📌 Project Overview**

This project is an interactive COVID-19 dashboard that allows users to visualize confirmed cases, deaths, recoveries, and active cases over time for different countries. The dashboard provides real-time insights through an intuitive interface built using Dash and Plotly.

By leveraging data analysis, visualization, and filtering capabilities, users can track the impact of COVID-19 globally or for specific regions.

**🛠️ Technologies Used**

Pandas & NumPy – Data preprocessing and manipulation

Plotly & Dash – Interactive visualizations and dashboard development

Seaborn & Matplotlib – Statistical data visualization

JupyterDash – Running the dashboard in Jupyter Notebook

**⚙️ Features**

✔ Interactive Country Selection – Users can choose any country or view global trends.

✔ Date Range Filtering – Allows users to analyze specific time periods.

✔ Dynamic Time-Series Charts – Visualizing Confirmed, Deaths, Recovered, and Active cases.

✔ Correlation Analysis – Heatmaps to explore relationships between different COVID-19 factors.

✔ Geospatial Insights – Mapping global COVID-19 trends using latitude and longitude data.

*📂 Dataset Information*

The dataset contains 24,590 records across 10 features, covering multiple countries and regions.

**Feature	Description**

Province/State	Specific state or province (if available)

Country/Region	Country where cases were reported

Lat	Latitude of the location

Long	Longitude of the location

Date	Date of the reported cases

Confirmed	Total confirmed COVID-19 cases

Deaths	Total reported deaths

Recovered	Total recovered cases

Active	Active cases (calculated as Confirmed - Deaths - Recovered)

WHO Region	World Health Organization regional classification

📊 **Key Insights**

🔹 Time-Series Analysis

The highest peaks of confirmed cases coincide with global pandemic waves.

Countries with higher testing & healthcare capacity tend to report more recoveries.

The active case count fluctuates based on the effectiveness of containment measures.

🔹 Correlation Analysis

Confirmed cases are strongly correlated with active cases.

Death rate varies by region, influenced by healthcare capacity and government response.

🔹 Geospatial Analysis

Countries with high population density tend to show higher COVID-19 cases.

Hotspots shift over time, reflecting different waves of the pandemic.

