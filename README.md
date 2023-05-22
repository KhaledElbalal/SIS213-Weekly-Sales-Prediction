# SIS213-Weekly-Sales-Prediction
Final Team Assignment for Introduction to Data Science (SIS213)

## Introduction and Goals

This project was completed as a team assignment for the Subject Introduction to Data Science (SIS213) at the Faculty of Computers and Artificial Intelligence, Cairo University. The team members involved in the project are:

- [Khaled Abdelreheam](https://github.com/KhaledElbalal)
- [Ahmed Khaled](https://github.com/moghazy17)
- [Yassin Saleh](https://github.com/yassinn07)
- [Malak Mahmoud](https://github.com/malakjjk)
- [Malak Gamal](https://github.com/malakg1)

The project was conducted under the supervision of Dr. Ayman El-Kilany and TA. Mohamed Ramadan.
A complete report, as well as all the visualizations and results could be found [here](https://github.com/KhaledElbalal/SIS213-Weekly-Sales-Prediction/blob/main/Data%20Science%20Report.pdf).

## Project Summary

The goal of this Data Science project was to analyze sales data from multiple stores in the U.S. and accurately predict weekly sales. The project involved the following steps:

1. Data Cleaning: The project utilized three main datasets: Fuel Prices, Sales, and Weather. The datasets were described, and necessary data cleaning steps were performed, including handling null values and merging the data based on dates.

2. Data Visualization: Various visualizations were created to gain insights into the data. These included line graphs, bar charts, histograms, and correlation plots. The visualizations helped identify patterns and trends in sales, store performance, and the relationship between sales and temperature.

3. Modeling: Three machine learning models, Linear Regression, Random Forest and XGBoost, were implemented to predict weekly sales. Data preprocessing techniques were applied, including feature selection and scaling. Model evaluation was performed using metrics such as Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, Mean Absolute Percentage Error, and R2 score.

4. KMeans: The data was clustered using KMeans algorithm to identify any patterns or groupings within the data. Silhouette Analysis and the Elbow Method were employed to determine the optimal number of clusters.

## Results and Next Steps

The analysis of the data revealed that the relationships in the data are mostly non-linear, as evidenced by the weak performance of the Linear Regression model and the strong performance of non-linear models like Random Forest and XGBoost. The Random Forest model yielded the best results for predicting weekly sales.

Next steps for the project may include collecting additional data on economic measures to further explain the results, focusing on the middle-numbered categories to understand their weaker performance compared to lower and higher numbered categories, and gathering more data on each category to improve clustering results.

For more details, please refer to the included [pdf file](https://github.com/KhaledElbalal/SIS213-Weekly-Sales-Prediction/blob/main/Data%20Science%20Report.pdf).
