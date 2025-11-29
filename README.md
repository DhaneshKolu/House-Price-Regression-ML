# House Price Prediction using Regression Neural Networks

## Project Overview
This project predicts house prices using the California Housing dataset.  
A regression neural network (MLP) was built using TensorFlow/Keras to estimate prices based on location and demographic features.

## Key Concepts
- Regression Neural Network  
- Feature Scaling (Standardization)  
- Train/Test Data Splitting  
- MSE Loss & MAE Metric  
- Error Visualization  
- Actual vs Predicted Plot  

## Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Scikit-learn  
- Matplotlib  

## Files in This Repository
- `House Pricing.ipynb` — Full preprocessing, model training, and evaluation  
- `requirements.txt` — Dependencies  
- `/assets` — Optional folder for graphs (Actual vs Predicted plot)

## Model Architecture
- Dense(64) — ReLU  
- Dense(32) — ReLU  
- Dense(16) — ReLU  
- Dense(1) — Linear (Regression Output)

Loss: **MSE**  
Optimizer: **Adam**  

## Results
- MAE: **~0.393**  
- Plotted Actual vs Predicted values  
- Visualized training + validation loss curves  
