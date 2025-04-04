# Gold Price Prediction

This project uses machine learning to predict gold prices based on various market indicators. The model is trained on historical data of gold prices and related financial indicators to forecast future gold prices.

## Project Overview

The goal of this project is to build a regression model that can accurately predict gold prices. This involves:

1. Data collection and preprocessing
2. Feature analysis and correlation study
3. Training a Random Forest Regressor
4. Model evaluation
5. Creating a predictive system for gold price forecasting

## Dataset

The dataset used in this project is `gold_price_data.csv`, which contains the following columns:

- Date: The date of the observation
- SPX: Standard and Poor's 500 index
- GLD: Gold price
- USO: United States Oil Fund price
- SLV: Silver price
- EUR/USD: Euro to US dollar exchange ratio

### Dataset Preview

The dataset contains daily observations from 2008 onwards, tracking gold prices along with other relevant financial indicators that may influence gold prices.

## Requirements

The following Python libraries are required to run the notebook:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

## Notebook Structure

1. **Importing Dependencies**: Required Python libraries are imported
2. **Data Collection and Processing**: Loading and preprocessing the dataset
3. **Exploratory Data Analysis**: 
   - Statistical measures
   - Correlation analysis
   - Distribution plots
4. **Feature Engineering**: Preparing features for model training
5. **Model Training**: Using Random Forest Regressor
6. **Model Evaluation**: Assessing model performance
7. **Visualization**: Plotting actual vs predicted prices

## Running the Project

1. Clone the repository or download the project files
2. Ensure all required libraries are installed
3. Open the `gold-price-prediction.ipynb` notebook in Jupyter Notebook
4. Run the notebook cells sequentially to see the analysis, model training, and predictions

## Results

The Random Forest Regressor model demonstrates strong predictive performance:
- Shows the relationship between various market indicators and gold prices
- Visualizes actual vs predicted gold prices
- Provides insights into factors influencing gold price movements

## Key Findings

- Correlation analysis reveals relationships between gold prices and other financial indicators
- The model captures market trends and patterns in gold price movements
- Visualization helps in understanding the model's predictive accuracy

## Conclusion

This project demonstrates how machine learning can be applied to financial market prediction, specifically for gold prices. The analysis provides valuable insights into the relationships between different market indicators and gold prices, while the model offers a tool for price prediction.

## Author
[Atharva Baikar](https://github.com/DarkGuardian641) 