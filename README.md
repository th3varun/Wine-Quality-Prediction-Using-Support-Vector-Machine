# Wine Quality Prediction Using Support Vector Machine

## Overview

This project predicts the quality of white wine using Support Vector Machine (SVM) classification. The dataset includes various chemical properties of the wine, which are used as features to predict its quality.

## Dataset Information

The white wine dataset contains twelve variables:
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol
12. quality

## Project Structure

1. **Import Libraries**
2. **Import Data**
3. **Data Exploration and Preprocessing**
4. **Feature Selection**
5. **Data Standardization**
6. **Train-Test Split**
7. **Model Training with SVM**
8. **Model Prediction and Evaluation**
9. **Binary Classification**
10. **Future Predictions**

## Dependencies

- pandas
- numpy
- scikit-learn

## Instructions

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/th3varun/Wine-Quality-Prediction-Using-Support-Vector-Machine.git
   cd wine-quality-prediction

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt

3. **Run the Jupyter Notebook:**
   Open the `Wine_Quality_Prediction_SVM.ipynb` file in Jupyter Notebook or JupyterLab to see the complete analysis and   
   results.

## Results

### Initial Model Evaluation

The initial SVM model was evaluated using a confusion matrix and classification report, providing insights into its accuracy and performance.

### Binary Classification

Wine qualities were re-labeled into two classes:
1. Quality 3, 4, 5 labeled as 0
2. Quality 6, 7, 8, 9 labeled as 1

The SVM model was retrained and evaluated for binary classification, showing improved performance.

### License

This project is licensed under the MIT License.

### Acknowledgments

1. The dataset was sourced from the `YBI Foundation`.
2. Special thanks to the creators and maintainers of the dataset.
