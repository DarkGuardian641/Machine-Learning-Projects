
# Simple Linear Regression on Canada's Per Capita Income

This project explores the use of Simple Linear Regression to predict the future per capita income of Canada based on historical data from 1970 to 2016. The predictions are made for the years 2020 and 2024.

## Project Overview

The goal of this project is to build a linear regression model that can predict the per capita income of Canada for future years. This involves:

1. Analyzing the historical data.
2. Training a linear regression model.
3. Making predictions for specific future years.
4. Visualizing the results.

## Dataset

The dataset used in this project is [canada_per_capita_income.csv](https://github.com/DarkGuardian641/Machine-Learning-Projects/blob/main/01%20-%20Simple%20Linear%20Regression/canada_per_capita_income.csv), which contains the following columns:

- Year : The year ranging from 1970 to 2016.
- Per capita income (USD) : The per capita income in US dollars for the corresponding year.

### Dataset Preview

Below is a preview of the `first 5 rows` of the dataset:

| year | per capita income (US$) |
|:----:|:-----------------------:|
| 1970 | 3399.30                 |
| 1971 | 3768.30                 |
| 1972 | 4251.18                 |
| 1973 | 4804.46                 |
| 1974 | 5576.51                 |

The dataset consists of **`47 entries`** in total, capturing a consistent trend in Canada's economic growth over nearly five decades.

## Requirements

The following Python libraries are required to run the notebook:

- numpy
- pandas
- matplotlib
- scikit-learn

Install the necessary libraries using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## Notebook Structure

1. **Introduction**: Overview of the problem statement and objectives.
2. **Importing Libraries**: Necessary Python libraries are imported.
3. **Loading and Exploring the Dataset**: The dataset is loaded, and basic data exploration is performed.
4. **Data Visualization**: Visualizations are created to understand the relationship between the year and per capita income.
5. **Model Training**: A Simple Linear Regression model is trained using the historical data.
6. **Predictions**: The model is used to predict the per capita income for the years 2020 and 2024.
7. **Results and Visualization**: The results of the predictions are displayed, along with a visualization of the regression line.
8. **Conclusion**: Final thoughts and potential next steps.

## Running the Project

1. Clone the repository or download the project files.
2. Ensure all required libraries are installed.
3. Open the [Simple_Linear_Regression.ipynb](https://github.com/DarkGuardian641/Machine-Learning-Projects/blob/main/01%20-%20Simple%20Linear%20Regression/Simple_Linear_Regression.ipynb) notebook in Jupyter Notebook or any other compatible environment.
4. Run the notebook cells sequentially to see the data analysis, model training, and predictions.

## Results

The Simple Linear Regression model provides the following predictions:

- **Predicted per capita income for 2020**: `$42960.57`
- **Predicted per capita income for 2024**: `$46399.99`

### Visualization

A plot showing the historical data and the regression line with predictions for 2020 and 2024 is included in the notebook.

## Conclusion

This project successfully demonstrates how Simple Linear Regression can be applied to predict future values based on historical data. The model provides a clear, interpretable prediction, which can serve as a foundation for more complex predictive models or economic analysis.

### Next Steps

- Explore additional features that may influence per capita income, such as inflation rates, GDP, and employment rates.
- Experiment with more advanced regression techniques or machine learning models.
- Perform cross-validation to ensure the robustness of the predictions.

## Author
[Atharva Baikar](https://github.com/DarkGuardian641)
