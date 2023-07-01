# predict-performance-of-game

# Student Performance Prediction

This project aims to predict student performance based on game play data. It utilizes machine learning algorithms such as Random Forest and XGBoost to train a model on the provided dataset.

## Dependencies

Before running this project, ensure you have the following dependencies installed:

- numpy
- pandas
- matplotlib
- seaborn
- dask
- scikit-learn
- xgboost

You can install them using the following command:
pip install -r requirements.txt


## Usage

1. First, install the required dependencies as mentioned above.

2. Make sure you have the dataset file `train.csv` available in the project directory.

3. Run the `main.py` script to perform the student performance prediction.


## Dataset

The dataset (`train.csv`) used for this project contains information about student game play sessions. It includes the following columns:

- `event_name`: The name of the event or action during the game session.
- `level`: The level of the game play session.
- `page`: The page related to the event.
- `coordinates`: The coordinates of the event in the game.
- `duration`: The duration of the game play session.
- `elapsed_time`: The time elapsed during the game play session.

## Feature Engineering

The `feature_engineer` function in the `main.py` code performs feature engineering on the dataset. It creates additional features based on different categories and numerical values. Additionally, it extracts date and time-related features from the `elapsed_time` column.

## Training and Evaluation

The code utilizes the provided dataset to train a machine learning model using Random Forest and XGBoost algorithms. It uses the engineered features to predict student performance.

## Results

The performance of the model is evaluated using the F1 score metric, which provides a measure of accuracy in making predictions.

## License

This project is licensed under the [MIT License](LICENSE).

