# Descriptive-Statistical-Analysis-of-Malaysian-Household-Income-2022-
A Python-based descriptive statistical analysis of Malaysian household income inequality across 200 districts using OpenDOSM data.

Malaysian Household Income Analysis (2022)
📌 Project Overview
This project performs a comprehensive descriptive statistical analysis of the 2022 Malaysian Household Income dataset at the district level. Using Python and the OpenDOSM API, this analysis investigates income distribution, regional disparities, and the relationship between mean and median income across 200 administrative districts.

The goal is to provide data-driven insights for businesses and policymakers to understand economic inequality and market segmentation in Malaysia.

📊 Key Findings
Income Skewness: The national distribution is positively skewed, with a Mean of RM 5,595.47 and a Median of RM 5,243.50, indicating that high-income outliers inflate the average.

Regional Disparity: A significant income gap (approx. RM 3,000) exists between high-earning states like Pulau Pinang and lower-earning states like Kelantan.

High Inequality Districts: The code identified Kota Kinabalu and Semporna as having the highest income gaps (>RM 2,300), suggesting significant internal wealth disparity.

🛠️ Technologies Used
Language: Python 3.x

Environment: Google Colab / Jupyter Notebook

Libraries: * Pandas: Data manipulation and cleaning

Requests: API data retrieval from OpenDOSM

Matplotlib & Seaborn: Data visualization (Bar charts, Scatter plots, Box plots)

📈 Visualizations Included
Median Income by State: A horizontal bar chart comparing the economic health of various states.

Mean vs. Median Relationship: A scatter plot featuring an Equality Line to visualize income inequality at the district level.

Income Distribution Box Plot: A visualization showing the spread and outliers of income within each state.

🚀 How to Run
Open the .ipynb file in Google Colab.

Run the first cell to fetch the latest data from the data.gov.my API(https://www.google.com/search?q=https://api.data.gov.my/data-catalogue%3Fid%3Dhh_income_district).

Execute the remaining cells to generate the statistical summary and plots.

📂 Dataset Source
Data is sourced from the Department of Statistics Malaysia (DOSM) via the OpenDOSM API(https://open.dosm.gov.my/).
