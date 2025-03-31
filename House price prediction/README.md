# Multiple Linear Regression

The given dataset shows us the area, number of bedrooms, and age of the house, along with the price in Monroe Township, NJ. Based on these values, find out the price of a home that has:

(i) 3000 sq. ft area, 3 bedrooms, 40 years old
<br>
(ii) 2500 sq. ft area, 4 bedrooms, 5 years old

## Project Overview

The goal of this project is to build a multiple linear regression model that can predict future cases or scenarios. This involves:

1. Analyzing the dataset and exploring correlations.
2. Training a multiple linear regression model.
3. Making predictions based on input values.

## Dataset

The dataset used in this project is [homeprices.csv](https://github.com/DarkGuardian641/Machine-Learning-Projects/blob/main/02%20-%20Multivariate%20Regression/homeprices.csv)

### Dataset Preview

Below is a preview of the first few rows of the dataset:

| Area | Bedrooms | Age | Price  |
|------|----------|-----|--------|
| 2600 | 3.0      | 20  | 550000 |
| 3000 | 4.0      | 15  | 565000 |
| 3200 | NaN      | 18  | 610000 |
| 3600 | 3.0      | 30  | 595000 |
| 4000 | 5.0      | 8   | 760000 |

## Requirements

The following Python libraries are required to run the notebook:

- numpy
- pandas
- scikit-learn

Install the necessary libraries using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Notebook Structure

1. **Introduction**: Overview of the problem statement and objectives.
2. **Importing Libraries**: Necessary Python libraries are imported.
3. **Loading and Exploring the Dataset**: The dataset is loaded, and basic data exploration is performed.
4. **Model Training**: A Multiple Linear Regression model is trained using the dataset.
5. **Predictions**: The model is used to make predictions on specified data.

## Running the Project

1. Clone the repository or download the project files.
2. Ensure all required libraries are installed.
3. Open the `Multiple_Linear_Regression.ipynb` notebook in Jupyter Notebook or any compatible environment.
4. Run the notebook cells sequentially to observe data analysis, model training, and predictions.

## Results

The [Multiple Linear Regression model](https://github.com/DarkGuardian641/Machine-Learning-Projects/blob/main/02%20-%20Multivariate%20Regression/Multiple_Linear_Regression.ipynb) provides the following sample predictions:

- **Prediction 1**: Price is `498408.25158031`
- **Prediction 2**: Price is `578876.03748933`

## Conclusion

This project demonstrates how Multiple Linear Regression can be applied to predict outcomes based on multiple features. 
The model provides interpretable predictions, which can be a foundation for more complex analyses.

## Author

[Atharva Baikar](https://github.com/DarkGuardian641)
