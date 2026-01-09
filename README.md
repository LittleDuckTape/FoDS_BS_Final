# Fundamentals of Data Science Source Code
Public Repository for Data Science Final Project

# Title: The Impact of Short-Form Video Exposure and Academic Functioning among Indonesian Students

# Abstract:
The widespread consumption of short-form video content on social media platforms has raised concerns regarding its potential impact on students’ attention span and academic outcomes. Short-form video platforms are designed to deliver rapid and highly engaging content, which may influence cognitive focus and learning behavior over time. This study examines the relationship between short-form video exposure, attention span, and academic performance among Indonesian students using a secondary survey dataset collected from senior high school and university students.

Data preprocessing was conducted to construct exposure, attention, and academic performance indices based on self-reported responses. Statistical analyses, including correlation and regression modeling, were applied to examine direct and indirect relationships between variables. In addition, machine learning models were employed to predict academic performance using exposure intensity and attention-related factors. The results indicate that higher exposure to short-form video content is associated with reduced attention span, which in turn relates to lower academic performance. Although predictive performance was moderate, the findings highlight the complexity of human learning behavior and emphasize attention span as a key mediating factor.

Index Terms—short-form video, attention span, academic performance, social media exposure, machine learning

# Project Overview:
The study combines:
- Exploratory Data Analysis (EDA)
- Partial Least Squares Structural Equation Modeling (PLS-SEM)
- Machine learning–based predictive modeling

The goal is to understand both explanatory relationships and predictive patterns in self-reported academic functioning.

# Methods:
- Survey data from 150 Indonesian students
- Composite indices constructed for:
  - Short-form video exposure
  - Attention difficulty
  - Academic functioning
- Predictive models:
  - Linear Regression
  - Random Forest Regression
  - Gradient Boosting Regression
  - XGBoost Regression

# Contacts:
Irene Angelina (irene.angelina@binus.ac.id)  
Heraisya Putri Thalib (heraisya.thalib@binus.ac.id)  
Andres Winson (andres.winson@binus.ac.id)

# Notes:
- Academic functioning is modeled as a **continuous variable**; regression is used instead of classification to avoid information loss from discretization.
- PLS-SEM analysis was conducted using SmartPLS with exported CSV data. Due the limitations of using a free license in SmartPLS, only up to 100 responses were analyzed.