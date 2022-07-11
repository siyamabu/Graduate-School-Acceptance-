# Predicting Graduate School Acceptance Probability

![Status Update](https://img.shields.io/badge/Status-Complete-green)
![GitHub top language](https://img.shields.io/github/languages/top/sverma1012/grad_rates?color=blue)

Badge [source](https://shields.io/)

## Key findings



## Authors

- [@siyamabu](https://www.github.com/siyamabu)

**Language and Tools:**<br />
* R :snake:
* R Notebook Notebook :notebook:
* GitHub :heart_eyes:

**Modules used:**<br />
* Pandas
* Scikit-learn
* Numpy
* Matplotlib
* Seaborn

**Environments Used:**<br />
* Windows 10 🪟

## Table of Contents

  - [Motivation](#motivation)
  - [Data source](#data-source)
  - [Methods](#methods)
  - [Quick Glance at the Results](#quick-glance-at-the-results)
  - [Lessons Learned and Recommendations](#lessons-learned-and-recommendations)
  - [Limitations and What Can Be Improved](#limitations-and-what-can-be-improved)
  - [Explore the Notebook](#explore-the-notebook)
  - [License](#license)

## Motivation 


## Data Source

- [Graduate Admissions)](https://www.kaggle.com/mohansacharya/graduate-admissions)

## Dataset Description

This data  is related to graduate school adimission probability. The dataset contains several factors which are generally considered as important during an individual’s application to master’s programs. This factors include Graduate Record Examination (GRE) Scores; TOEFL Scores; Statement Of Purposes (SOP); Letter Of Recommendations (LOR); College GPA (CGPA); and University Ratings. 

## Methods

1. Exploratory Data Analysis
    * Historgrams of each quantitative predictor variable and an assessment of pairwise correlations between pairs of quantitative predictor variable.  
2. First Order Model with All Predictors
    * 
3. Second Model with the transormed variable vs All Predictors
    * 
4. Third Model using Stepwise Regression
   * 
5. Fourth Model using Stepwise Regression with Centered Interaction Effects

## Quick Glance at the Results

Correlations between variables.

![heatmap](pictures/life_correlation_heatmap.png)

A comparison of the best results from each model.

![graphx](pictures/model_results.png)

The Residuals vs Predicted Strength for the best linear regression model.

![graph1](pictures/residuals_vs_predicted_linear_regression.png) 

The Observed Strength vs Predicted Strength for the best linear regression model.

![graph2](pictures/observed_strength_vs_predicted_strength_linear%20regression.png)

The Residuals vs Predicted Strength for the best decision tree regression model. 

![graph3](pictures/residuals_vs_predicted_decision_tree_regression.png)

The Observed Strength vs Predicted Strength for the best decision tree regression model.

![graph4](pictures/observed_strength_vs_predicted_strength_decision_tree_%20regression.png)

5 highest feature importance scores from the best decision tree model.

![graphy](pictures/feature_importance.png) 

## Lessons Learned and Recommendations
-

## Limitations and What Can Be Improved
- 

## Explore the Notebook

To explore the notebook file [here](https://github.com/siyamabu/Life-Expectancy/blob/main/life_expectancy_prediction.ipynb)

## License

MIT License

Copyright (c) 2022 Siyabonga Mabuza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Learn more about [MIT](https://choosealicense.com/licenses/mit/) license


