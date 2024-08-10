# Time Series Regression Analysis

This repository contains the code and results of a Time Series Regression Analysis conducted to model and predict the unit sales for thousands of items sold at different Favorita stores. The analysis leverages various statistical and machine learning techniques to understand the temporal dynamics and make accurate predictions.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
4. [Results](#results)
5. [Dependencies](#dependencies)
6. [How to Run the Code](#how-to-run-the-code)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This project aims to perform a time series regression analysis on training data, test data, stores data, oil price data and a few others The primary objective is to build a model that can accurately predict the unit sales for lots of items sold at different Favorita stores.

The analysis includes:
- Data preprocessing and feature engineering
- Model selection and training
- Performance evaluation
- Visualization of results

## Dataset

The datasets used for this analysis  are all in .csv format and were obtained from 3 sources: a database, OneDrive and a GitHub repository. 
It includes train.csv, training data,test.csv

The datasets include:
- train.csv
- training data
- test.csv
- transaction.csv
- sample_submission.csv
- stores.csv
- oil.csv
- holidays_events.csv

## Methodology

### 1. Data Preprocessing
- Handling missing values
- Feature scaling
- Time-based feature extraction

### 2. Model Selection
- Linear Regression
- Baseline Model
- Support Vector Regression
- Random Forest Regression
- Arima
- Sarima

### 3. Model Training and Evaluation
- Training process
- Cross-validation
- Performance metrics used (e.g., RMSE, MAE)

### 4. Visualization
- Time series plots
- Predicted vs Actual values

## Results

The best-performing model was Linear Regression with an RMSE of 7.4 (the lowest amongst all the models).

## Dependencies

To run the code, you need to have the following installed:

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
  

You can install the required packages using:

```bash
pip install -r requirements.txt
```

## How to Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/briansiaw5/Time_Series_Regression_Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd briansiaw5
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Time_Series_Regression_Analysis.ipynb
   ```

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

