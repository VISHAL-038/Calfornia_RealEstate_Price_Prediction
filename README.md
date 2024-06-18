# California Housing Dataset

## Overview
This dataset is based on the 1990 California census and serves as an introductory dataset for learning machine learning algorithms. It requires basic data cleaning and offers an understandable set of variables, making it ideal for teaching fundamental machine learning concepts.

### Context
The dataset is featured in Chapter 2 of Aurélien Géron's book "Hands-On Machine Learning with Scikit-Learn and TensorFlow". It provides insights into housing attributes in various California districts, derived from census data.

### Content
The dataset includes the following columns:

1. **longitude**: Longitude of the house location.
2. **latitude**: Latitude of the house location.
3. **housing_median_age**: Median age of houses in the district.
4. **total_rooms**: Total number of rooms in the district.
5. **total_bedrooms**: Total number of bedrooms in the district.
6. **population**: Total population in the district.
7. **households**: Total number of households in the district.
8. **median_income**: Median income of households in the district (measured in tens of thousands of US Dollars).
9. **median_house_value**: Median house value in the district (measured in US Dollars).
10. **ocean_proximity**: Proximity of the district to the ocean/sea.

### Acknowledgements
- Original dataset: This dataset is a modified version of the California Housing dataset available from [Luís Torgo's page (University of Porto)](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html).
- Featured in: "Hands-On Machine learning with Scikit-Learn and TensorFlow" by Aurélien Géron.
- Initial paper: Pace, R. Kelley, and Ronald Barry. "Sparse spatial autoregressions." Statistics & Probability Letters 33.3 (1997): 291-297.

### Inspiration
Explore machine learning basics using this dataset:
- [Machine learning basics in R kernel](https://www.kaggle.com/camnugent/basic-machine-learning-with-r-on-california-housing)
- [Python based introductory tutorial](https://github.com/ageron/handson-ml/tree/master/datasets/housing)

## Usage
1. **Data Cleaning**: Perform basic data cleaning and preprocessing steps.
2. **Exploratory Data Analysis (EDA)**: Understand data distributions and relationships.
3. **Feature Engineering**: Create new features if necessary.
4. **Modeling**: Build predictive models such as Linear Regression and Random Forest.
5. **Evaluation**: Assess model performance using appropriate metrics.

## Files
- `housing.csv`: Main dataset file containing housing data.
- `README.md`: Overview of the dataset and instructions.
- `notebooks/`: Jupyter notebooks for EDA, preprocessing, and modeling.
- `scripts/`: Python scripts for data handling, modeling, and evaluation.

## Requirements
- Python 3
- Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

### License
This dataset is licensed under the [CC0: Public Domain License](https://creativecommons.org/publicdomain/zero/1.0/). You can freely use, modify, and distribute the dataset, even for commercial purposes, without asking for permission.

## Author
- Dataset compiled by Aurélien Géron
