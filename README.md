# House Price Prediction (Python, Machine Learning)

> Generates sample house data, trains six models and compares which one predicts the price best.

## Origin

Based on a repository by [ranim699](https://github.com/ranim699).

## What it does

The program generates 1,000 synthetic houses (rooms, area, age, location ...) with a price, prepares the data, trains models such as linear regression and random forest, and evaluates them with metrics and charts.

## Tech stack

| Technology | Used for |
|---|---|
| Python | Language of the whole project. |
| pandas / numpy | Tables and numerical computing. |
| scikit-learn | Machine learning models and cross-validation. |
| matplotlib / seaborn | Charts. |
| Jupyter Notebooks | Step-by-step analysis in `notebooks/`. |

## Project structure

| Path | Content |
|---|---|
| `main.py` | Runs the whole pipeline. |
| `src/data_generator.py` | Generates the sample data. |
| `src/data_preprocessor.py` | Cleans the data and creates new features. |
| `src/model_trainer.py` | Trains and evaluates the models. |
| `config/config.py` | All settings in one place. |

## How to run

1. Install Python 3 and run `pip install -r requirements.txt`.
2. Run `python main.py`.
3. Results are saved in `data/`, `models/` and `results/`.

## Key concepts

- Data preparation: missing values, scaling, feature engineering.
- Train/test split and cross-validation.
- Metrics: R² (how much is explained), RMSE/MAE (average error).

## Known issues

- The data is synthetic – very good scores say little about real markets.
- Quite large for beginners; start by understanding linear regression only.

## Ideas for improvements

- Use a real data set (e.g. rents of a German city).
- Store the data in an SQL database (SQLite) and load it from there.
- A small input form that predicts the price of one house.

## My changes

- _(describe here what you built or improved yourself)_
