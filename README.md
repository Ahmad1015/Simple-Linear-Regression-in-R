# Simple Linear Regression in R

This repository contains R code for performing Simple Linear Regression. Simple Linear Regression is a statistical method used to model the relationship between a single independent variable and a dependent variable. In this specific case, we are analyzing the relationship between years of experience and salary.

## Getting Started

These instructions will help you understand the code and run it on your local machine.

### Prerequisites

Before running the code, you'll need to have R and the necessary libraries installed. You can install the required libraries using the following commands in your R console:

```R
install.packages('caTools')
install.packages('ggplot2')
```
Code Overview
The R script consists of the following key steps:
- Importing the dataset: The code reads a dataset named 'Salary_Data.csv' using read.csv.

- Splitting the dataset: It randomly splits the dataset into a training set (2/3 of the data) and a test set (1/3 of the data) using sample.split from the 'caTools' library.

- Fitting Simple Linear Regression: The code uses the 'lm' function to fit a linear regression model to predict salary based on years of experience using the training set.

- Predicting the Test set results: It uses the trained model to make predictions on the test set.

- Visualizing the Training and Test set results: The code uses 'ggplot2' to create scatter plots with the actual data points (red dots) and the regression line (blue line) for both the training and test sets.

## Usage
You can use this code as a reference for performing Simple Linear Regression in R. To run the code, follow these steps:

- Ensure you have R and the required packages installed.

- Place your dataset (in this case, 'Salary_Data.csv') in the same directory as the R script.

- Open the R script in RStudio or any other R environment.

- Run the code step by step or all at once.

- Observe the generated scatter plots and regression lines to analyze the relationship between years of experience and salary.

## Contributing
Feel free to contribute to this repository by making improvements or adding more features to the Simple Linear Regression analysis.

## Credits

This project was inspired by the "Machine Learning A-Z™: AI, Python & R + ChatGPT Bonus [2023]" course on Udemy, created by:

- Kirill Eremenko
- Hadelin de Ponteves
- SuperDataScience Team
- Ligency Team

I acknowledge and thank the instructors and teams behind this course for providing valuable knowledge and resources. You can find the course on Udemy at https://www.udemy.com/course/machinelearning/.

Feel free to explore and modify the code to suit your needs and continue your learning journey in machine learning and data science.
