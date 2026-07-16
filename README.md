# UBDT-Capstone-Weather
🚀 SpaceX Launch Analysis Project
Overview
This repository presents a comprehensive data‑science workflow analyzing SpaceX Falcon 9 launch outcomes. The project follows the IBM Data Science Capstone (Coursera) structure, progressing from data collection to predictive modeling.

##Contents
| Notebook | Description |
| **01_data_collection_api** | Retrieves launch data using the SpaceX REST API. |
| **02_webscraping** | Extracts additional launch details from public web sources. |
| **03_data_wrangling** | Cleans, merges, and prepares datasets for analysis. |
| **04_eda_sql** | Performs SQL‑based exploratory analysis using SQLite. |
| **05_eda_dataviz** | Visualizes launch patterns and success rates. |
| **06_launch_site_location** | Maps launch sites and analyzes geospatial factors. |
| **07_dash_app** | Builds an interactive dashboard using Plotly Dash. |
| **08_machine_learning_prediction** | Trains classification models to predict launch success. |


##Tools & Libraries
Python, pandas, NumPy, scikit‑learn
Plotly Dash, Folium, SQLite
SpaceX API, BeautifulSoup


Getting Started
###Clone the repository:

bash
git clone https://github.com/<your‑username>/spacex‑launch‑analysis.git

###Install dependencies:

bash
pip install -r requirements.txt
Run notebooks sequentially in JupyterLab or VS Code.

###Launch the dashboard:

bash
python 07_spacex_dash_app-skv.py


#Results
Prediction accuracy: ≈ 85 % using logistic regression and decision‑tree models.

##Key insights:

Booster reuse strongly correlates with successful launches.

Launch sites closer to the equator improve payload efficiency.

The interactive dashboard visualizes success rates by site and booster version.



Objective
To predict the likelihood of successful Falcon 9 launches and visualize insights through interactive dashboards.

References
IBM Data Science Capstone (Coursera): Course Link (coursera.org)

SpaceX API Documentation: GitHub Repository


## Final Presentation
You can view the complete presentation here:  
[Final_Project_Presentation.pdf](presentation/Final_Project_Presentation.pdf)
