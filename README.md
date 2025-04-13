# House Price Prediction using PyTorch

This project demonstrates a regression model built using PyTorch to predict house prices based on the California Housing dataset. The model is trained, evaluated, and visualized with various configurations to optimize performance.

## Features

- **Data Preprocessing**: Standardizes the dataset using `StandardScaler`.
- **Model Architecture**: Fully connected neural network with configurable layers, neurons, and activation functions.
- **Training**: Implements a training loop with Mean Squared Error (MSE) loss and Adam optimizer.
- **Evaluation**: Evaluates the model on a test set and visualizes results.
- **Hyperparameter Tuning**: Experiments with different numbers of layers, neurons, activation functions, learning rates, and batch sizes.
- **Visualization**: Includes plots for actual vs. predicted values and error distribution.

## Requirements

Install the required Python libraries using the following command:

```bash
pip install torch scikit-learn pandas numpy matplotlib