## Match Group Churn and Feature Analysis Project
# Interaction Term Analysis and Statistical Modeling Project

## Overview

This project aims to analyze and visualize the interaction effects of various features on user behavior, specifically focusing on multi-session user behavior. Using advanced statistical modeling techniques, such as Multinomial Logistic Regression, the project explores the impact of individual features and their interactions, ultimately providing insights that guide decision-making in user engagement strategies.

## Purpose of the Project

The purpose of this project is to:
- Identify significant interaction terms among various user attributes that affect multi-session behavior.
- Quantify the impact of these interactions using beta coefficients from a Multinomial Logistic Regression model.
- Provide a statistical foundation for prioritizing A/B testing and optimization efforts.

## Goal of the Project

The main goal of this project is to:
- Understand how different user attributes and their interactions influence the likelihood of a user engaging in multi-session behavior.
- Visualize the beta coefficients of these interaction terms to highlight the most impactful factors.
- Assess the feasibility of A/B testing or Multivariate Testing (MVT) for the identified interaction terms to guide further experimental design.

## How the Goal was Achieved

### 1. Data Preparation
- **Data Generation**: A synthetic dataset was generated with 2.2 million users, containing various user attributes such as age, gender, profile completeness, and device type.
- **Feature Engineering**: Interaction terms between features were created to explore how combined effects influence multi-session behavior.

### 2. Statistical Modeling
- **Multinomial Logistic Regression**: A Multinomial Logistic Regression model was fitted to the data, including main effects and interaction terms. This model was used to estimate the beta coefficients of the interaction terms.
- **Beta Coefficient Analysis**: The regression results were analyzed to extract and visualize the beta coefficients of the interaction terms, highlighting the most significant factors.

### 3. Visualization
- **Beta Coefficient Plot**: A bar plot of the beta coefficients was created to visually represent the magnitude and direction of each interaction term’s impact on multi-session behavior.

### 4. Feasibility Analysis of A/B and MVT Testing
- **A/B Testing Feasibility**: Assessed the practicality of conducting A/B tests on all 21 interaction terms, concluding that simultaneous testing is not feasible due to sample size, complexity, and duration constraints.
- **MVT Feasibility**: Explored the potential of Multivariate Testing (MVT) for the interaction terms and determined that even MVT is not practical for all terms due to similar challenges.

### Key Insights:
- **Prioritization of Interaction Terms**: The analysis identified key interaction terms with the highest impact, allowing for prioritization in future testing and optimization efforts.
- **Strategic Guidance**: The project provides a data-driven approach to understanding user behavior, guiding decisions in user engagement and marketing strategies.

## Project Structure

- `data/`: Contains the generated dataset used for the analysis.
- `scripts/`: Python scripts for data preparation, modeling, and visualization.
- `results/`: Includes the output plots and analysis summaries.
- `README.md`: Overview and detailed explanation of the project.

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourprojectname.git
   cd yourprojectname

