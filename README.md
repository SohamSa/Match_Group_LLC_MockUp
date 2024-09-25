# Match Group Churn and Feature Analysis Project
## Interaction Term Analysis and Statistical Modeling Project

## Overview

At Match Group, I joined the team at a critical juncture when Match.com was struggling with a significant issue: **66% of potential users were abandoning the platform before completing the registration process**. The registration consisted of 23 steps, including personal identification information, demographic details, and questions designed to enhance matchmaking. My primary task was to uncover the reasons behind this high abandonment rate and provide actionable insights to improve customer retention.

## Purpose of the Project

The purpose of this project is to:
- **Identify key factors and interaction effects** that influence user behavior, particularly those leading to high registration abandonment rates.
- **Provide data-driven insights** to enhance user retention by targeting the most impactful features and interactions.

## Goal of the Project

The main goal of this project was to:
- Understand how different user attributes and their interactions influenced the likelihood of a user engaging in multi-session behavior, particularly completing registration and remaining on the platform.
- Develop actionable strategies to **reduce churn and improve overall user retention** on Match.com.

## How the Goal was Achieved

### 1. Data Collection and Preparation

I started by building a comprehensive dataset of 2.2 million users, extracting data from hundreds of Microsoft SQL Server databases. This involved writing complex SQL queries, utilizing joins, window functions, and subqueries to collect and aggregate the necessary data. Once the dataset was complete, I transferred it into Python Jupyter Notebook for further analysis.

Given the data sensitivity and non-disclosure agreements, the exact data cannot be shared publicly. Therefore, for this project showcase, a mock dataset was generated using Python, simulating the data extraction and processing steps as closely as possible to the real-world scenario.

### 2. Exploratory Data Analysis (EDA)

With the dataset in Python, I began by conducting Exploratory Data Analysis (EDA). This phase allowed me to dive deep into the data, uncovering trends and patterns related to user behavior throughout the registration funnel. By familiarizing myself with the dataset, I gained a clear understanding of the key features that might be influencing user dropout rates.

### 3. Statistical Significance Testing

The next step was to determine which features were statistically significant in predicting whether users would complete the registration and stay on the platform for more than 24 hours. I implemented inferential statistical methods, using p-values, f-scores, and t-tests to assess the importance of individual features and their interactions.

The target variable in my analysis was the **Multi_session column**, a probabilistic indicator of whether a user stayed on the app for 24 hours after registration, where 1 indicated retention and 0 represented churn.

### 4. Modeling Interaction Effects

To model this relationship, I used **Multinomial Logistic Regression**, which allowed me to estimate the probability of a user remaining on the app based on the identified features and their interactions. Beta coefficients from the model provided insights into the impact of each interaction term, guiding the prioritization of subsequent testing.

### 5. Validation through A/B Testing

After building the model, I validated the findings using A/B testing, focusing on key interaction terms. This involved testing various permutations of features, interactions of features, and excluding certain features to observe their impact on the user retention rate. 

Through a combination of rigorous analysis, modeling, and A/B testing, I identified several key insights that led to significant improvements. 

### Key Insights and Results:
- The analysis identified critical interaction terms contributing most to user retention and registration completion.
- The final solution resulted in a **15% reduction in churn**, meaning 15% more users completed the registration process and stayed on the platform compared to before. This increase in customer retention directly improved the overall user experience and engagement on Match.com.

### Important Disclaimer
Due to the sensitivity of the data and company policies, it was necessary to use randomly generated mock data for this public showcase. As a result, **the results and inferences from these findings may not match exactly with those derived from real data. The focus of this project is not on the specific findings, but on demonstrating the analytical approach and methodology used to tackle the problem.** The preprocessing steps to create datasets from scratch in SQL and further multivariate testing are not feasible to demonstrate here due to data access limitations and the absence of deployment infrastructure linked to company databases.

## Project Structure

- `data/`: Contains the generated dataset used for the analysis.
- `scripts/`: Python scripts for data preparation, modeling, and visualization.
- `results/`: Includes the output plots and analysis summaries.
- `README.md`: Overview and detailed explanation of the project.

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourprojectname.git
   git clone https://github.com/SohamSa/Mock_Match_Group.git
   cd yourprojectname
   cd Mock_Match_Group

   OR for Download:
   

