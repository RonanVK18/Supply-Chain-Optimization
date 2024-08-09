# Supply Chain Optimization Using Neural Networks

Welcome to the **Supply Chain Optimization Using Neural Networks** repository! This project leverages neural networks to enhance supply chain operations through demand forecasting, lead time prediction, and stock optimization. The goal is to provide a robust framework for predicting future demand and lead times, and determining the optimal stock levels to minimize costs and improve efficiency.

## Project Overview

This project aims to optimize supply chain operations by predicting demand and lead times using neural networks. It also employs the Estimated Order Quantity (EOQ) method to determine the optimal stock levels required to meet future demand while minimizing total costs, including holding costs, ordering costs, and stock-out costs.

### Key Objectives

1. **Demand Forecasting:** Predict future product demand based on historical data.
2. **Lead Time Prediction:** Forecast the lead times for various products.
3. **Optimal Stock Calculation:** Use the EOQ method to determine the optimal stock levels.

## Features

- **Neural Network Models:** Implemented for demand forecasting and lead time prediction.
- **Data Preprocessing:** Includes data cleaning, normalization, and feature engineering.
- **Stock Optimization:** Utilizes the EOQ method to find the optimal stock quantities.
- **Visualization:** Provides tools to visualize forecast results and stock levels.

## Dataset

The dataset used for this project is sourced from Kaggle. It includes historical sales data, which is essential for training and validating the neural network models.

## Installation

To get started with this project, follow these installation steps:

1. **Clone the Repository:**

2. **Create a Virtual Environment (Optional but recommended):**

3. **Install Required Packages:**

## Usage

After setting up the environment, you can use the provided scripts to run the project. Here's a brief guide on how to use the code:

1. **Prepare the Dataset:**
   Ensure your dataset is in the correct format and placed in the `data/` directory.

2. **Run Data Preprocessing:**
  
3. **Train the Neural Network Models:**
  
4. **Predict and Optimize:**
  
5. **View Results:**
   Results and visualizations will be saved in the `results/` directory.

## Model Details

### Demand Forecasting Model

- **Architecture:** Multi-Layer Perceptron (MLP) or Long Short-Term Memory (LSTM) network.
- **Input Features:** Historical sales data, date features, and other relevant attributes.
- **Output:** Predicted sales quantity for future periods.

### Lead Time Prediction Model

- **Architecture:** MLP or LSTM network.
- **Input Features:** Historical lead time data, product features.
- **Output:** Predicted lead time for future orders.

## Estimated Order Quantity Method

The EOQ method is used to determine the optimal order quantity that minimizes total inventory costs. The formula is:

\[ EOQ = \sqrt{\frac{2DS}{H}} \]

where:
- \( D \) = Demand rate
- \( S \) = Ordering cost per order
- \( H \) = Holding cost per unit per year

The code implements this formula to calculate the optimal stock levels based on forecasted demand and lead times.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
