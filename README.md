# Stock Price Prediction Model

## Overview

This project focuses on predicting stock price movements for the S&P 500 index using various machine learning techniques. It involves fetching historical stock data, performing feature engineering, training models, and evaluating their performance.

## Features

- **Data Collection**: Retrieves historical data for the S&P 500 index using the `yfinance` library.
- **Feature Engineering**: Generates features such as lagged prices, rolling averages, and trend indicators to improve model performance.
- **Model Training**: Utilizes machine learning models like Random Forest and Gradient Boosting Classifiers to predict price movements.
- **Model Evaluation**: Assesses model performance using precision, recall, F1 score, and ROC-AUC score.

## Getting Started

To get started with this project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/varsityyy/Predicting-Stock-Market.git
```



### 2. Navigate to the Project Directory

```bash
cd repository
```

### 3. Install Dependencies

Ensure you have Python installed. Then, install the required packages using `pip`:

```bash
pip install -r requirements.txt
```

### 4. Run the Jupyter Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then, open `Stock_Price_Prediction.ipynb` and execute the cells to run the analysis and model training.

## Project Structure

- `Stock_Price_Prediction.ipynb`: The main Jupyter Notebook containing the analysis, feature engineering, and model training code.
- `data/`: Directory containing raw and processed data files.
- `requirements.txt`: List of Python packages required for the project.
- `README.md`: This file.

## Usage

1. **Data**: The project uses historical data for the S&P 500 index. The data is fetched from Yahoo Finance using `yfinance` and saved in CSV files.
2. **Feature Engineering**: Features like lagged prices, rolling means, and trends are computed and used for training the models.
3. **Model Training**: Several machine learning models are trained and evaluated to predict whether the price will go up or down.
4. **Evaluation**: The performance of the models is evaluated using various metrics to determine their effectiveness.

## Example Output

The models produce predictions on whether the S&P 500 price will increase or decrease. Evaluation metrics include:

- Precision
- Recall
- F1 Score
- ROC-AUC Score

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- `yfinance` for retrieving financial data.
- `scikit-learn` for machine learning algorithms and tools.
- Jupyter Notebook for interactive development and analysis.

## Contact

For any questions or feedback, please open an issue on the [GitHub repository](https://github.com/varsityyy/Predicting-Stock-Market).

