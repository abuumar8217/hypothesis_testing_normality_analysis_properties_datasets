# Hypothesis Testing and Normality Analysis with Real-World Datasets

## Project Overview
This project focuses on performing detailed hypothesis testing and normality analysis on two real-world datasets:
1. **Housing Data** (Sale Prices)
2. **Cancer Data** (Tumor Characteristics)

The goal of this project is to assess the normality of each dataset, apply appropriate statistical tests based on data distributions, and interpret the results to draw conclusions about the relationships within the data.

## Key Concepts
- **Normality Testing:** Checking whether data follows a normal distribution using the Shapiro-Wilk test, histograms, and Q-Q plots.
- **Hypothesis Testing:** Applying statistical tests like T-tests (for comparing two groups) and Chi-Square tests (for categorical data) to determine if there are significant differences or associations within the data.
- **Data Transformation:** Using transformations like logarithmic functions to make non-normally distributed data more suitable for hypothesis testing.

## Datasets
1. **Housing Data (Sale Prices):** A dataset containing sale prices of homes. We'll perform a Shapiro-Wilk test for normality and use a T-test to compare sale prices between different neighborhoods.
2. **Cancer Data (Tumor Characteristics):** A dataset containing information about tumor characteristics such as radius size. We perform normality tests and a Chi-Square test to examine the relationship between tumor size and diagnosis.

## Key Libraries Used
- `numpy`: For numerical operations and array manipulation.
- `pandas`: For data manipulation and analysis.
- `scipy`: For statistical tests like Shapiro-Wilk, T-test, and Chi-Square tests.
- `matplotlib` & `seaborn`: For data visualization (histograms, box plots, Q-Q plots, etc.).

## Steps Involved
1. **Normality Testing:** Using the Shapiro-Wilk test, histograms, and Q-Q plots to check if data is normally distributed.
2. **Hypothesis Testing:** 
   - **T-Test**: Comparing means between two groups (e.g., comparing sale prices between neighborhoods).
   - **Chi-Square Test**: Examining the association between categorical variables (e.g., tumor size categories and diagnosis).
3. **Data Transformation:** Applying a logarithmic transformation to make the data more normally distributed and re-evaluating the hypothesis tests.
4. **Interpretation:** Interpreting the results of hypothesis tests and drawing conclusions based on p-values and confidence intervals.

## Installation
To run the code in this repository, you will need to install the following Python libraries:

```bash
pip install numpy pandas scipy matplotlib seaborn
