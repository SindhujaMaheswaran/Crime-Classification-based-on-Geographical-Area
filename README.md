# Crime-Classification-based-on-Geographical-Area

Comprehensive records of crime incidents in Los Angeles since 2020, sourced from original reports.

This **intermediate machine learning project** aims to develop a sophisticated, data-driven system to categorize and analyze crime patterns across various neighborhoods in Los Angeles from 2000 to 2023. By leveraging advanced machine learning techniques, this project addresses critical concerns related to crime and safety in specific geographical areas, ultimately contributing to enhanced community safety and informed decision-making.

## Data Acquisition
The dataset for this project was sourced from the **Los Angeles Police Department**. It includes a comprehensive collection of reported crimes, detailing:
- Type of crime
- Location
- Date and time of occurrence
- Victim information

Dataset Source : https://catalog.data.gov/dataset/crime-data-from-2020-to-present 

Dataset Used : final_dataframe 

# Framed Data

After completing the data cleaning and feature engineering processes, the dataset was organized into a structured format suitable for analysis.

The framed data comprises several key features that provide valuable insights into crime patterns and demographics in Los Angeles

## Data Cleaning Process
The data preparation phase involved several key steps to ensure reliability and accuracy:
1. **Renaming Columns**: Improved readability by renaming cryptic columns, e.g., changing 'VICT_AGE' to 'Victim Age.'
2. **Handling Missing Values**: Employed various techniques to address missing data:
   - Categorical data: filled with the mode or created a separate category.
   - Numerical data (e.g., victim age): used mean or median imputation.
3. **Addressing Outliers**: Used statistical methods like the Interquartile Range (IQR) to identify and manage outliers, particularly in victim age data.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, TensorFlow/Keras (for RNN), Seaborn, Plotly
- **Data Visualization**: Matplotlib, Plotly

# Algorithms

Linear Regression

XGBoost

Random Forest Classifier

Recurrent Neural Network

# Future Work

Hyperparameter Tuning

Different Models

Creation of new attributes

Normalization

