This project focuses on analyzing the IMDB Movies dataset to predict movie revenue using machine learning techniques. By exploring and modeling relationships between different movie features (such as budget, genre, score, and country), the project aims to identify factors that contribute to a movie's financial success.

Results Overview

Best-performing Model: Decision Forest Regression

R-squared value (Best Model): 0.6659

Key Predictors: Budget, Score, Country, Genre, Original Language

<img width="640" alt="Screenshot 2024-09-16 at 12 53 49 AM" src="https://github.com/user-attachments/assets/4b4ff785-b774-43ef-84fa-8f736d38fc51">
<img width="354" alt="Screenshot 2024-09-16 at 12 54 47 AM" src="https://github.com/user-attachments/assets/0443077a-5591-405d-9c55-5c6440b2446c">

Project Objectives

The main objective of this project is to predict movie revenue using independent variables from the IMDB dataset. The process involved:

Data Preprocessing: Cleaning the dataset by handling missing values, normalizing variables, and ensuring data consistency.

Exploratory Data Analysis (EDA): Understanding the relationships between movie features (e.g., budget, score, genre) and revenue through visualizations and statistical testing.

Budget

Ho: We expect that Budget will have no effect on Revenue. 

<img width="642" alt="Screenshot 2024-09-16 at 12 58 57 AM" src="https://github.com/user-attachments/assets/4b781326-b308-463a-94e1-7cce3d40ca2f">

Summary: There is a strong effect of Budget on Revenue that is very reliable. We tested all non-linear transformations and found that Polynomial produced the best R2 value of 0.48948 and a p-value of < 0.0001 (reject Null Hypothesis).

Genre

Ho: We expect that there will be no effect by Genre on Revenue

<img width="628" alt="Screenshot 2024-09-16 at 12 57 00 AM" src="https://github.com/user-attachments/assets/8d3dedfa-acad-461b-bdb6-612e0e754bad">

Summary: There is an effect by Genre on Revenue with a f-stat value of 56.2825183 and a p-value of 0.09760088 (<0.5) -> reject Null Hypothesis. 

See more details in Final Project.pdf

Feature Engineering: Creating new relevant features and transforming existing ones to improve prediction accuracy.

<img width="615" alt="Screenshot 2024-09-16 at 12 47 45 AM" src="https://github.com/user-attachments/assets/491351d1-b426-4880-bd22-b6563d66c44f">

Model Training and Testing: Applying machine learning algorithms such as Linear Regression, Bayesian Linear Regression, and Decision Forest Regression to predict movie revenue.

<img width="647" alt="Screenshot 2024-09-16 at 12 48 31 AM" src="https://github.com/user-attachments/assets/6a514b24-278f-4c64-8584-e23b468accba">

<img width="645" alt="Screenshot 2024-09-16 at 12 49 28 AM" src="https://github.com/user-attachments/assets/7b607db3-e7a5-4392-b7ec-59309898f05a">

Model Evaluation and Fine-tune: Comparing model performance using R-squared and RMSE values to select the best model for predicting revenue.

Visualization: Tableau Dashboard

A comprehensive dashboard was created to visualize key findings from the analysis, including:

<img width="601" alt="Screenshot 2024-09-16 at 12 46 13 AM" src="https://github.com/user-attachments/assets/900b524f-4015-44ac-ac9a-40153d9ba115">

Key Findings

Budget and Revenue: Higher production budgets are strongly associated with higher revenues.
Movie Score: Movies with higher IMDB scores generally perform better in terms of revenue.
Country of Origin: Certain countries (e.g., Mauritius, Taiwan) have higher average movie revenues.
Genre Impact: Genres like Adventure, Action, and Fantasy generate higher revenue compared to others.
Status Effect: Movies in the "Released" stage earn significantly more than those in production or post-production.

