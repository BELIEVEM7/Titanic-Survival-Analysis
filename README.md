# Titanic Survival Analysis (Data Analysis) 

This project focuses on analyzing passenger data from the Titanic disaster to uncover patterns and insights related to survival outcomes. Using data cleaning, transformation, and visualization techniques, we explore how factors such as age, gender, ticket class, and family presence influenced survival rates.

## Tools Used:
- Python (Pandas, NumPy)
- Data visualization I used Tableau
- Jupyter Notebook for interactive analysis
- Microsoft Excel for data cleaning

## Dataset: [Titanic - Machine Learing from Disaster](https://www.kaggle.com/competitions/titanic/data)

## Loading Data
My project begins with loading data from CSV files using the pandas library, segregating the data into train and test datasets. These datasets contain crucial information about the Titanic passengers, forming the foundation of my analysis.

## Data Cleaning

I used excel for my data cleaning, this was a pivotal stage in my analysis. In this stage I:
- Dropped irrelevant colummns such as Name, Cabin and Ticket columns.
- Filled in blanks in Age with the median of the Age column.
- Created a new column named Family_Size, it was calulated using the following formula: SibSp + Parch + 1
- Replace missing values in `Embarked with the mode of the column.

## Exploratory Data Analysis (EDA)

Here I used Tableau for better visualization, I have provided a screenshot of how my final visualization looked like:

![Screenshot](https://github.com/BELIEVEM7/Titanic-Survival-Analysis/blob/9e762d52e1c3434026df0d0a9bacde083e53fe15/Tableau/Screenshot%20of%20EDA.jpeg)







