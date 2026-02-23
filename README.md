# MSc Artificial Intelligence Dissertation  
## Predicting Player Minutes in Professional Football Using Machine Learning

This repository contains the full codebase for my MSc Artificial Intelligence dissertation, conducted in collaboration with Lincoln City FC.
The objective of the project was to develop and explore machine learning models capable of predicting player minutes played, using engineered representations of playing style and contextual performance data.
!! Due to confidentiality agreements, the dataset, its contents, feature names, results, performance metrics, tables, and figures are not included in this repository.

## Project Overview
Due to feasibility limitations from data the problem was reframed from a standard direct prediction task into a style-compatibility feature engineered prediction.
The project involved
- Exploratory data analysis and feasibility modelling
- Playing style modelling
- Feature engineering and similarity metrics
- Automated feature selection
- Tree ensembles and ensembles of ensembles ML models
- Model interpretation

Four methodological variations were implemented using similar skeleton code to demonstrate structured experimentation and problem-solving

- Method 1: Merged dataset, manual selection
- Method 2: Split dataset, removed manual selection
- Method 3: Included more temporal and contextual diversity in the data (increased dataset size)
- Method 4: Included target transformation to address skewed target distribution

## Repository Structure
- 'EDA/' - Exploratory data analysis code and baseline modelling
- 'Main Model/' - Final modelling pipelines and method variants

##Technical Stack
Python • scikit-learn • XGBoost • SHAP • pandas • NumPy • Matplotlib • Seaborn
