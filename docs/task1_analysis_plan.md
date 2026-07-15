# Task 1 – Analysis Plan

## Project Objective

The objective of this project is to investigate how major geopolitical events, economic shocks, wars, sanctions, and OPEC policy decisions have influenced Brent crude oil prices between 1987 and 2022. The analysis aims to identify statistically significant structural changes in the price series and associate those changes with real-world events.

---

# Planned Data Analysis Workflow

The project follows the steps below.

## 1. Data Acquisition

Obtain historical Brent crude oil prices covering May 1987 through September 2022.

---

## 2. Data Loading

Import the dataset into Python using Pandas.

Verify data integrity and variable types.

---

## 3. Data Cleaning

* Convert dates into datetime format.
* Check for missing values.
* Remove duplicate observations if necessary.
* Preserve the original dataset.

---

## 4. Exploratory Data Analysis

Perform exploratory analysis to understand:

* historical trends
* price distribution
* volatility
* rolling statistics
* summary statistics

---

## 5. Time Series Analysis

Investigate:

* trend
* stationarity
* volatility clustering
* autocorrelation
* partial autocorrelation
* log returns

---

## 6. Bayesian Change Point Modeling

Develop a Bayesian Change Point Model using PyMC to estimate:

* change point location
* mean price before change
* mean price after change
* uncertainty surrounding each estimate

---

## 7. Event Matching

Compare detected change points with:

* OPEC decisions
* wars
* sanctions
* financial crises
* pandemics

---

## 8. Quantitative Interpretation

Estimate how prices changed before and after each detected change point.

---

## 9. Dashboard Development

Develop a Flask backend and React frontend for interactive exploration of:

* historical prices
* detected change points
* associated geopolitical events

---

## 10. Reporting

Summarize findings, limitations, assumptions, and recommendations.
