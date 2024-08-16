# Recipe Popularity Prediction

This project predicts the popularity of recipes by analyzing website traffic data. The goal is to help the product management team select recipes that are likely to generate high traffic on the website, ultimately increasing user engagement and subscriptions.

## Project Overview

The product management team currently selects recipes to feature on the homepage manually. Selecting popular recipes can boost website traffic by up to 40%, directly impacting subscription rates. This project uses machine learning models to predict which recipes will lead to high traffic, with an accuracy of at least 80%.

## Business Goals

- Predict recipes that will lead to high traffic.
- Ensure predictions are correct at least 80% of the time.

## Project Structure

The repository contains the following files:

- `notebook.ipynb`: The Jupyter Notebook containing data validation, exploratory analysis, model development, evaluation, and business metrics analysis.
- `slides.pdf`: A presentation summarizing the project, key findings, and recommendations.
- `dataset.csv`: The dataset used for the analysis.

## Key Findings

- Logistic Regression was selected as the final model, achieving a precision score of 81% and an accuracy score of 77%.
- The model meets the business requirement of predicting high-traffic recipes 80% of the time.

## Recommendations

- Deploy the Logistic Regression model to predict high-traffic recipes.
- Monitor and update the model regularly to maintain accuracy and precision.
- Improve data quality by validating and sanitizing incoming data and collecting additional relevant features.

# Getting Started

## Prerequisites

- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, scikit-learn

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/wesonga/Recipe-Popularity-Prediction-An-Analysis-of-Site-Traffic-Data.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Recipe-Popularity-Prediction-An-Analysis-of-Site-Traffic-Data
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebook:

    ```bash
    jupyter notebook Recipe_Popularity_Prediction.ipynb
    ```

## Usage

- **Exploratory Data Analysis**: Understand the data and discover patterns that influence recipe popularity.
- **Model Development**: Train and evaluate machine learning models to predict high-traffic recipes.
- **Business Metrics**: Compare the model’s performance with the business goals and assess its impact.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improving the project.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
