# Titanic-Dataset
"Explore Titanic dataset with interactive visualizations. Analyze passenger demographics, survival rates, ticket fares and more in a user-friendly dashboard."

Streamlit Dashboard for Titanic Dataset
This is a Streamlit dashboard for exploring the famous Titanic dataset, which contains information about passengers who were aboard the Titanic when it sank on April 15, 1912. The dataset includes information about each passenger's age, sex, class, fare, cabin, and whether they survived the disaster or not.

Getting Started
To use this dashboard, you will need to have Python 3 installed on your machine. You can then install the required packages by running the following command in your terminal:

pip install streamlit pandas matplotlib seaborn

Once you have installed the packages, you can launch the dashboard by running the following command:

streamlit run titanic_dashboard.py

This will open a browser window where you can interact with the dashboard.

Features
The dashboard includes the following features:

Data Exploration
The first section of the dashboard allows you to explore the data by viewing summary statistics, visualizations, and a table of the raw data. You can use the dropdown menus to select which variables to view, and you can adjust the bins and other parameters of the visualizations.

Survival Analysis
The second section of the dashboard allows you to perform survival analysis on the dataset, which involves examining how different variables affect the likelihood of survival. You can select which variables to include in the analysis using the dropdown menus, and you can adjust the confidence level and other parameters of the analysis.

Prediction
The third section of the dashboard allows you to make predictions about whether a hypothetical passenger would have survived the Titanic disaster based on their characteristics. You can enter values for the passenger's age, sex, class, and other variables using the sliders and dropdown menus, and the dashboard will use a machine learning model to make a prediction about their survival.

Data Sources
The Titanic dataset used in this dashboard is available from the Kaggle website at https://www.kaggle.com/c/titanic/data. The dataset includes two CSV files: train.csv, which contains the training data, and test.csv, which contains the test data.

Credits
This dashboard was created by [Your Name] using the Streamlit framework and the Titanic dataset. The dashboard is provided under the MIT license.
