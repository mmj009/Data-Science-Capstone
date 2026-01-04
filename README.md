**Project Overview**
This project predicts the success of SpaceX Falcon 9 first-stage landings. By analyzing historical launch data, we aim to determine the factors that contribute to a successful booster recovery, which significantly reduces launch costs (estimated at $62 million per launch).

**Tech Stack**
Languages: Python 3.x, SQL
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Folium, Plotly Dash, Scikit-Learn
Tools: Jupyter Notebooks, IBM DB2, GitHub, LibreOffice

**Methodology**
Data Collection: Extracted data from the SpaceX REST API and scraped mission details from Wikipedia using BeautifulSoup.
Data Wrangling: Cleaned data, handled missing values, and performed one-hot encoding for categorical variables.
Exploratory Data Analysis (EDA): Used SQL and visualization tools to identify trends in payload mass, orbit types, and launch sites.
Interactive Analytics: Developed geospatial maps using Folium and an interactive dashboard using Plotly Dash.
Machine Learning: Built and tuned four classification models (Logistic Regression, SVM, Decision Tree, and KNN) using GridSearchCV.

**Key Results**
Predictive Accuracy: All optimized models achieved an accuracy of 83.33% on the test set.
Success Drivers: Higher success rates are strongly correlated with newer booster versions (Block 5) and specific orbits like SSO and VLEO.
Site Insights: Proximity to coastlines and transportation infrastructure is a key strategic factor for all SpaceX launch sites.

Repository Structure
/notebooks: Contains Jupyter notebooks for each phase of the project.
/presentation: The final Capstone Project PDF.
