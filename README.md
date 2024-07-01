# Wine Quality Prediction Project

This project predicts the quality of wine based on various chemical properties using machine learning techniques. The dataset includes both red and white wine samples with attributes such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality ratings.

## Objective

The objective of this project is to build a predictive model that can accurately classify wine quality based on its chemical composition.

## Data Source

The dataset used in this project is sourced from the UCI Machine Learning Repository:
- [Wine Quality Dataset (Red Wine)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- [Wine Quality Dataset (White Wine)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

## Project Structure

- **1. Import Libraries:** Python libraries used for data manipulation, visualization, and modeling.
  
- **2. Import Data:** Loading the wine quality dataset into pandas DataFrames for analysis.
  
- **3. Describe Data:** Summary statistics and basic information about the dataset.
  
- **4. Data Visualization:** Visualizing distributions and correlations among the features.
  
- **5. Data Preprocessing:** Handling missing values, removing duplicates, and encoding categorical variables.
  
- **6. Define Target Variable and Feature Variables:** Separating the dataset into features (X) and target variable (y).
  
- **7. Train Test Split:** Splitting the data into training and testing sets for model evaluation.
  
- **8. Modeling:** Training a Random Forest Classifier on the training data.
  
- **9. Model Evaluation:** Evaluating the performance of the trained model using accuracy score and confusion matrix.
  
- **10. Prediction:** Using the trained model to predict wine quality based on user input.

## How to Use

To run this project, follow these steps:
1. Clone this repository to your local machine.
2. Install the necessary Python libraries listed in `requirements.txt`.
3. Execute the Jupyter Notebook or Python script `wine_quality_prediction.ipynb` to see the analysis and results.

## Dependencies

Ensure you have the following Python libraries installed:
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- ipywidgets (for interactive prediction)

## Contributors

- [Aswin Krishna]

## License

This project is licensed under the MIT License - see the LICENSE file for details.

