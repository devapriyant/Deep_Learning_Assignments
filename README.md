#  House Price Prediction using Artificial Neural Networks

This repository contains two deep learning assignments that predict house prices using the **California Housing Dataset**. 
The projects demonstrate the implementation of **Artificial Neural Networks (ANN)** and **Multilayer Feed Forward Neural Networks (MLP)** for solving a regression problem.

---

##  Project Objectives

- Load and explore the California Housing Dataset.
- Perform data preprocessing and feature standardization.
- Build and train deep learning regression models.
- Evaluate model performance using regression metrics.
- Predict house prices for unseen data.
- Save the trained models for future use.

---

#  Assignment 1 – Artificial Neural Network (ANN)

## Description

This assignment implements a basic Artificial Neural Network (ANN) to predict house prices. 
The dataset is preprocessed using **StandardScaler**, and the ANN is trained with three hidden layers to learn the relationship between housing features and house prices.

### Model Architecture

- Input Layer (8 Features)
- Hidden Layer 1 – 64 Neurons (ReLU)
- Hidden Layer 2 – 32 Neurons (ReLU)
- Hidden Layer 3 – 16 Neurons (ReLU)
- Output Layer – 1 Neuron (Linear)

### Model Configuration

- Optimizer : Adam
- Loss Function : Mean Squared Error (MSE)
- Metric : Mean Absolute Error (MAE)
- Batch Size : 32
- Epochs : 100

---

#  Assignment 2 – Multilayer Feed Forward Neural Network (MLP)

## Description

This assignment develops a Multilayer Feed Forward Neural Network (MLP) with a deeper architecture for house price prediction.
The model uses additional hidden layers to improve learning capability and regression performance.

### Model Architecture

- Input Layer (8 Features)
- Hidden Layer 1 – 128 Neurons (ReLU)
- Hidden Layer 2 – 64 Neurons (ReLU)
- Hidden Layer 3 – 32 Neurons (ReLU)
- Hidden Layer 4 – 16 Neurons (ReLU)
- Output Layer – 1 Neuron (Linear)

### Model Configuration

- Optimizer : Adam
- Learning Rate : 0.001
- Loss Function : Mean Squared Error (MSE)
- Metric : Mean Absolute Error (MAE)
- Batch Size : 32
- Epochs : 120

---

#  Dataset

**Dataset Name:** California Housing Dataset

**Source:** Scikit-learn (`fetch_california_housing()`)

### Features

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

**Target Variable:** Median House Price

---

#  Technologies Used

- Python 3.x
- TensorFlow
- Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

#  Repository Structure

```
House-Price-Prediction/
│
├── Assignment1_ANN.ipynb
├── Assignment2_MLP.ipynb
├── HousePriceANN.keras
├── HousePrice_MLP.keras
├── requirements.txt
├── README.md
└── images/
```

---

#  Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

#  Output

The notebooks include:

- Dataset Preview
- Dataset Information
- Statistical Summary
- Missing Values Check
- Correlation Heatmap
- Model Summary
- Training Process
- Training vs Validation Loss
- Performance Metrics
- Actual vs Predicted Comparison
- Scatter Plot
- Sample House Price Prediction
- Model Saving

---

#  Trained Models

The trained models are saved as:

- `HousePriceANN.keras`
- `HousePrice_MLP.keras`

---

#  How to Run

1. Clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the notebooks in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.
5. View the evaluation metrics and generated plots.
6. The trained models will be saved automatically after execution.

---

#  Conclusion

Both deep learning models successfully predict house prices using the California Housing Dataset. 
The ANN and MLP models demonstrate the effectiveness of neural networks for regression tasks through proper preprocessing, 
model training, and performance evaluation. The project highlights the practical application of deep learning techniques in real-world house price prediction.
