Vehicle Theft Analysis
Project Overview
This project focuses on analyzing vehicle theft data from 2021 and 2022 to uncover patterns, trends, and predictive factors related to vehicle theft incidents. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and building a logistic regression model for prediction.

Contents
Data Cleaning and Preprocessing: Handling missing values, removing duplicates, and correcting data types.
Exploratory Data Analysis (EDA): Visualizing the distribution of vehicle types, models, and temporal patterns in theft incidents.
Feature Engineering: Creating new features to improve the predictive power of the dataset.
Model Building and Evaluation: Developing a logistic regression model to predict the likelihood of a vehicle being a certain type based on other features.
Summary of Findings: Key insights and conclusions drawn from the analysis.
Data
The raw data for this project was sourced from Our World in Data. Due to file size limitations, the raw data is not included in this repository. Instead, you can download it directly from the provided link.

Files in the Repository
Cleaned Data: cleaned_vehicle_theft_data.csv
Jupyter Notebook: vehicle_theft_analysis.ipynb
Instructions
Download the Dataset: If you wish to work with the raw data, download it from Our World in Data.
Clone the Repository: Clone this repository to your local machine using the command:
bash
Copy code
git clone https://github.com/yourusername/vehicle-theft-analysis.git
Install Dependencies: Ensure you have the necessary Python libraries installed. You can install them using:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook: Open the vehicle_theft_analysis.ipynb notebook and run the cells to reproduce the analysis.
Summary of Findings
Commonly Stolen Vehicles: Station wagons, saloons, hatchbacks, and trailers constitute the majority of stolen vehicles. Station wagons stand out as the most frequently stolen type.
Temporal Patterns: Vehicle thefts show a notable increase in 2022 compared to 2021. The third month of the year exhibits the highest number of thefts, with the first two months also showing significant theft occurrences.
Model Insights: The top three most stolen vehicle models are Hilux, Courier, and Demio, indicating specific targets for theft incidents.
Model Accuracy: The logistic regression model achieved perfect accuracy in predicting vehicle types, indicating strong predictive power. Cross-validation confirmed the model's reliability.
Conclusion
This project provided a comprehensive analysis of vehicle theft data from 2021 and 2022, offering valuable insights into theft patterns and predictive factors. The findings can inform effective theft prevention strategies and enhance public safety.
