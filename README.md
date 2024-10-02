# Diabetes Prediction Using Pima Dataset (Linear Regression)

## Project Overview

This project aims to predict the likelihood of diabetes in women based on various health factors using the Pima Indian Diabetes Database. The analysis utilizes exploratory data analysis (EDA) and logistic regression modeling to provide insights into diabetes risk factors.

## File Structure

```
Diabetes-Risk-Prediction-using-Linear-Regression/
├── data/
│   ├── pima-indians-diabetes.csv          # Dataset containing patient records(Training Data)
│   ├── ToPredict.csv                      # Dataset containing patient records(Testing Data)
├── notebooks/
│   ├── exploratory_data_analysis.ipynb    # Jupyter Notebook for EDA
│   ├── diabetes_prediction_model.ipynb     # Jupyter Notebook for model training
├── scripts/
│   ├── preprocess.py                       # Python script for data preprocessing
│   ├── model.py                            # Python script for model training and evaluation
├── requirements.txt                        # Required Python packages
├── README.md                               # Project documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Diabetes_Prediction
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Exploration**:
   - Open `notebooks/exploratory_data_analysis.ipynb` to perform EDA on the dataset.

2. **Model Training**:
   - Run `notebooks/diabetes_prediction_model.ipynb` to train the logistic regression model and evaluate its performance.

3. **Preprocessing and Modeling**:
   - Modify and run `scripts/preprocess.py` for data cleaning and preprocessing.
   - Use `scripts/model.py` for model training and prediction.

## Results

- Achieved an accuracy of 68.67% and an AUC score of 0.59 in predicting diabetes.
- Key features affecting diabetes risk include glucose levels, BMI, and number of pregnancies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
