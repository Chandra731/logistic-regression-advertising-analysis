# Logistic Regression for Advertisement Click Prediction

This project explores the use of logistic regression to predict whether an internet user will click on an advertisement based on their demographic and behavioral data.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Logistic Regression Model](#logistic-regression-model)
- [Results and Evaluation](#results-and-evaluation)
- [Usage](#usage)
- [License](#license)

## Introduction

This project aims to build a model that can assist advertisers in better targeting their campaigns, potentially increasing click-through rates and improving overall campaign effectiveness.

## Dataset

The dataset used for this project is a simulated advertising dataset containing the following features:

- `Daily Time Spent on Site`: Consumer time on site in minutes
- `Age`: Customer age in years
- `Area Income`: Average income of the geographical area of the consumer
- `Daily Internet Usage`: Average minutes a day the consumer is on the internet
- `Ad Topic Line`: Headline of the advertisement
- `City`: City of the consumer
- `Male`: Whether or not the consumer was male (1 for male, 0 for female)
- `Country`: Country of the consumer
- `Timestamp`: Time at which the consumer clicked on the ad or closed the window
- `Clicked on Ad`: Target variable (1 for clicked, 0 for did not click)

## Exploratory Data Analysis (EDA)

The EDA section of the Jupyter Notebook includes:

- Histograms and distribution plots to visualize the distribution of features like age.
- Joint plots to explore relationships between features, such as age and area income.
- Pair plots to get an overview of the relationships between all pairs of features.

## Logistic Regression Model

The logistic regression model is trained on features like daily time spent on the site, age, area income, and daily internet usage to predict whether a user will click on an ad.

## Results and Evaluation

The model is evaluated using a classification report, providing metrics like precision, recall, F1-score, and accuracy. The report helps assess the model's performance in classifying ad clicks.

## Usage

1. Clone the repository: `git clone https://github.com/your-username/logistic-regression-advertising-analysis.git`
2. Install required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook logistic_regression_project.ipynb`
4. Explore the EDA, model training, and evaluation results.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
