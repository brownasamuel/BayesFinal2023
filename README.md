The Crossfit Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


This repository contains multiple Jupyter Notebooks that explore a Kaggle dataset related to CrossFit athletes. 
The analysis includes loading the dataset, performing exploratory data analysis (EDA), and building two Bayesian linear regression models to predict Deadlift Weight and 5K Run Time. 
The models are then evaluated using trace, posterior and counterfactual plots to identify the most important predictors. The final Jupyter Notebook is called ...

## Table of Contents

- [Introduction](#introduction)
- [Content](#content)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

In order to find controllable predictors' effects on strength and endurance performance, code was developed to analyze and model variable relationship based on approximately 18,000 observations in the cleaned dataset. All the Bayesian Linear Regression models were built with specified priors. Then the resulting predictor coefficients' posterior distributions were examined to determine which specific variables had the largest impact on fitness results.

## Content

[Final Code](https://github.com/brownasamuel/BayesFinal2023/blob/main/Actual_Final_Project.ipynb): The Jupyter Notebook containing the final completed analysis. <br>
[Final_Document](https://github.com/brownasamuel/BayesFinal2023/blob/main/Final_Paper.pdf): The PDF containing our final paper<br>
[Crossfit Dataset](https://www.kaggle.com/datasets/ulrikthygepedersen/crossfit-athletes?select=athletes.csv): The Kaggle dataset used for the analysis.

## Installation
(requires Python 3.10)

Project dependencies include (numpy, pandas, arviz, seaborn, matplotlib.pyplot, pymc and textwrap).
Make sure to download the Crossfit Dataset above and replace the athletes variable in the Jupyter Notebook with its local filepath.

See local download instructions below to get the code and install dependencies.


```bash
git clone https://github.com/brownasamuel/BayesFinal2023
npm install
```

## Usage

Run the entire notebook which will create all necessary models and generate resultant plots required to draw necessary conclusions.

## Contributing

Samuel Brown, Patrick Dunnington and Will Sivolella developed the data analysis, model development and result testing.
