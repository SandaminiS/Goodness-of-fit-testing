# Goodness-of-Fit Tests in High-Dimensional Logistic Regression

## Overview
This project was completed as a term project for STA7734: Statistical Asymptotic Theory in Big Data. The focus is on assessing goodness-of-fit tests in high-dimensional settings, specifically within the context of logistic regression. The dataset used for this analysis is the Toxicity Dataset from the UCI Machine Learning Repository.

## Project Background
Goodness-of-fit tests are crucial for assessing how well observed data aligns with a specific distribution or model, typically framed within the hypothesis testing framework (H0: the model fits vs. H1: the model does not fit). While traditional methods, such as the Chi-Square test and Kolmogorov-Smirnov test, are effective for low-dimensional data, they often fail in high-dimensional settings where the number of covariates exceeds the number of observations. This limitation has prompted the development of new methodologies tailored for generalized linear models (GLMs) in high-dimensional contexts, focusing on detecting misspecification in the conditional mean function. The challenge lies in consistent estimation of model parameters under sparsity assumptions, especially when considering potential nonlinear relationships, making it essential to explore the application of goodness-of-fit tests in high-dimensional logistic regression.

## Dataset
- **Source**: UCI Machine Learning Repository
- **Dataset Name**: Toxicity Dataset

## Objectives
- Assess the effectiveness of goodness-of-fit tests in high-dimensional logistic regression.
- Develop methodologies to detect model misspecification in high-dimensional settings.

## Methodology
- **Goodness-of-Fit Tests**: Employ various tests to evaluate model fit.
- **Logistic Regression**: Analyze the applicability of logistic regression in high-dimensional contexts.
- **Sparsity Assumptions**: Investigate the role of sparsity in model parameter estimation.

## Results and Discussion
- Summarize findings related to the performance of goodness-of-fit tests in high-dimensional logistic regression.
- Discuss the implications of the results for statistical modeling in big data contexts.

## Getting Started
To run this project locally, please follow these steps:
1. Clone the repository: `git clone <repository_url>`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Run the analysis scripts: `python analysis.py`

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Dataset obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/toxicity).
