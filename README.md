# Heart Disease Prediction using Artificial Neural Network

## Project Overview

This project implements a Feed-Forward Artificial Neural Network (ANN) for Heart Disease Prediction using Python and NumPy.

The neural network is implemented from scratch, demonstrating forward propagation, sigmoid activation, backpropagation, and gradient-based weight updates.

## Dataset

- Heart Disease Prediction dataset.
- Input file: Heart_Disease_Prediction.csv.
- Target variable: Heart Disease.

## Data Preprocessing

- Target variable encoding using LabelEncoder.
- Separation of input features and target variable.
- Feature standardization using StandardScaler.

## Neural Network Architecture

- Input layer: Dataset features.
- Hidden layer: 10 neurons.
- Output layer: 1 neuron.
- Activation function: Sigmoid.

## Training Configuration

- Learning rate: 0.1
- Training epochs: 5,000
- Loss function: Mean Squared Error (MSE)
- Training method: Backpropagation
- Weight optimization: Gradient-based updates

## Implementation Features

1. Dataset loading and preprocessing.
2. Label encoding.
3. Feature standardization.
4. Neural network weight initialization.
5. Forward propagation.
6. Sigmoid activation.
7. Backpropagation.
8. Training loss visualization.
9. Binary classification and training accuracy calculation.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Structure

Heart-Disease-Prediction-Neural-Network/
├── Heart_Disease_Prediction_ANN.ipynb
├── README.md
└── requirements.txt

## Execution

1. Open the notebook in Google Colab.
2. Upload Heart_Disease_Prediction.csv.
3. Execute the notebook cells sequentially.
4. Observe the training loss graph.
5. Examine the model's predictions and training accuracy.

