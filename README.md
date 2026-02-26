# Snack Consumer Sensory Data Analysis

This repository contains a comprehensive data analysis of sensory evaluation data for four different snack products across two global markets (US and UK). The goal of the analysis is to understand consumer liking and the sensory drivers that influence those preferences.

## Project Overview

The project is structured through a sequence of Jupyter notebooks, each addressing a specific stage of the data science workflow:

1.  **Exploratory Data Analysis (EDA):** `01_data_load_and_eda_exp_design.ipynb`
    *   Initial data cleaning and validation.
    *   Visualizing the distribution of consumer liking.
    *   Analysis of the experimental design (balanced 4-product evaluation per respondent).
2.  **Liking Difference Analysis:** `02_liking_difference.ipynb` & `03_post-hoc_analysis.ipynb`
    *   Quantifying significant differences in liking between the four snack products.
    *   Post-hoc testing to identify which specific products outperform others.
3.  **Sensory Drivers of Liking:** `04_sensory_drivers_of_liking.ipynb`
    *   Correlation analysis between sensory attributes (Sweetness, Crunchiness, Oiliness, Aftertaste) and Overall Liking.
    *   Multicollinearity checks using Variance Inflation Factor (VIF).
    *   Multiple Linear Regression modeling to identify positive and negative drivers of liking.
4.  **Market Comparison:** `05_market_difference_analysis.ipynb`
    *   Segmented analysis comparing consumer behavior in the US vs. UK markets.
5.  **Perceptual Mapping:** `06_perpetual_mapping.ipynb`
    *   Spatial representation of products based on their sensory profiles.

## Dataset Summary

The analysis is based on the `snack_consumer_sensory_dataset.csv` located in the `data/` directory.

*   **Total Observations:** 880 entries.
*   **Unique Respondents:** 220.
*   **Markets:** US and UK.
*   **Products Evaluated:**
    *   A_CrunchyClassic
    *   B_SweetSpicy
    *   C_LightBaked
    *   D_RichCheesy
*   **Attributes:** Sweetness, Crunchiness, Oiliness, Aftertaste, and Overall Liking.

## Environment Setup

The repository includes a pre-configured Python virtual environment (`.venv`). To run the notebooks, ensure you have the following core libraries installed:

*   `pandas`
*   `numpy`
*   `matplotlib`
*   `seaborn`
*   `statsmodels`
*   `scikit-learn`
*   `scipy`

## Usage

1.  Activate the virtual environment.
2.  Open Jupyter Lab/Notebook.
3.  Run the notebooks in sequential order (01 to 06) to follow the complete logic of the analysis.
