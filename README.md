# Missile Launch Planning Using Linear Regression

## Overview

This project investigates the relationship between the extension length of a synthetic rubber band and the distance travelled after launch. The objective is to develop a predictive statistical model that estimates the required stretch length to reach a desired target distance.

The study combines experimental data collection, statistical modeling, regression analysis, and diagnostic validation to construct a practical prediction framework.

---

**Project Year:** 2023


## Key Results

* Approximately **180 experimental observations**
* **9 randomly selected rubber bands** tested
* **Pearson Correlation:** 0.8875
* **R²:** 0.78
* **RMSE:** 40.65
* Predictive model with confidence and prediction intervals

---

## Sample Visualization

![Pooled Data Graph](latex/figures/Figure%202%20Pooled%20data%20graph.png)

*Figure: Scatter plot of stretch length versus travelled distance using pooled experimental observations.*

---

## Experimental Design

* Multiple stretch lengths were tested under controlled conditions.
* Repeated measurements were collected and averaged to reduce experimental error.
* Multiple rubber bands were used to mitigate wear-and-tear effects.
* Experimental data were compiled and analyzed using statistical software.

---

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
2. Exploratory Data Analysis
3. Regression Modeling
4. Diagnostic Validation
5. Confidence and Prediction Interval Estimation

---

## Prediction and Confidence Intervals

![Prediction and Confidence Interval Graph](latex/figures/Figure%208%20Prediction%20and%20confidence%20interval%20graph.png)

The fitted model was used to generate confidence and prediction intervals, allowing uncertainty in future predictions to be quantified.

---

## Model Diagnostics

![Q-Q Residuals Plot](latex/figures/Figure%205%20Q-Q%20residuals%20plot.png)

Diagnostic procedures were performed to assess:

* Linearity
* Homoscedasticity
* Residual Normality
* Overall model adequacy

The diagnostic results supported the use of a linear regression model for the collected data.

---

## Tools and Technologies

* R
* Python
* NumPy
* Matplotlib
* Linear Regression
* Statistical Modeling
* LaTeX

---

## Repository Structure

```text
README.md                # Project overview
report.pdf               # Final project report
datasets/                # Experimental datasets
latex/                   # LaTeX source files
latex/figures/           # Graphs and visualizations
```

---

## Project Deliverables

* Experimental dataset
* Statistical analysis
* Regression model
* Diagnostic evaluation
* Prediction framework
* Full LaTeX report

---

## Author

**Rahul Ganguly**

M.Sc. Statistics
