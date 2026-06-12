# Missile Launch Planning Using Linear Regression

![Pooled Data Scatter Plot](latex/figures/Combined.jpg)

## Project Overview

This project investigates the relationship between the extension length of a synthetic rubber band and the distance travelled after launch. The problem is formulated as a missile launch planning task, where the objective is to determine the required stretch length to reach a desired target distance.

Using experimentally collected data, a predictive statistical model was developed to estimate travel distance and quantify prediction uncertainty.

## Objectives

* Collect experimental data from a rubber-band projectile system.
* Study the relationship between stretch length and distance travelled.
* Develop a predictive regression model.
* Estimate prediction uncertainty through statistical analysis.
* Evaluate model assumptions using diagnostic techniques.

## Experimental Design

* Approximately **180 observations** were collected.
* **9 randomly selected rubber bands** were used to reduce wear-and-tear effects.
* Multiple measurements were recorded at each stretch length.
* Repeated observations were averaged to reduce experimental error.
* Data were compiled and analyzed using statistical software.

## Statistical Methodology

The relationship between stretch length and travelled distance was modeled using **Ordinary Least Squares (OLS) Linear Regression**.

### Model Form

```text
Distance Travelled = β₀ + β₁ × Stretch Length + ε
```

where:

* β₀ = Intercept
* β₁ = Regression coefficient
* ε = Random error term

### Analysis Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Scatter Plot Visualization
5. Linear Regression Modeling
6. Diagnostic Assumption Checking
7. Prediction and Confidence Interval Estimation

## Key Results

* Sample Size: **~180 observations**
* Rubber Bands Tested: **9**
* Pearson Correlation Coefficient: **0.8875**
* Coefficient of Determination (**R²**): **0.78**
* Root Mean Squared Error (**RMSE**): **40.65**

The results indicate a strong positive linear relationship between stretch length and travel distance.

## Prediction and Confidence Intervals

![Prediction Interval Plot](latex/figures/prediction.jpg)

The fitted model was used to generate prediction and confidence intervals, allowing uncertainty in future predictions to be quantified.

## Model Diagnostics

![Q-Q Plot](latex/figures/QQ_plot.jpg)

Diagnostic plots were used to assess:

* Linearity
* Homoscedasticity
* Residual Normality
* Overall model adequacy

These checks supported the suitability of a linear regression model for the collected data.

## Tools and Technologies

* R
* Python
* NumPy
* Matplotlib
* Linear Regression
* Statistical Modeling
* LaTeX

## Repository Structure

```text
README.md                # Project description
report.pdf               # Final project report
datasets/                # Experimental datasets
latex/                   # LaTeX source files
latex/figures/           # Graphs and plots
```

## Project Deliverables

* Experimental dataset
* Statistical analysis
* Regression model
* Diagnostic evaluation
* Prediction framework
* Full LaTeX report

## Author

**Rahul Ganguly**
