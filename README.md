# Breast Cancer Prediction

This project predicts whether a breast cancer tumor is malignant or benign using machine learning. The model uses the **Breast Cancer Wisconsin dataset** and applies **MLPClassifier** for classification.

## Project Structure
- `train_model.py`: Contains the model training code.
- `app.py`: Streamlit app that takes user input and predicts whether the tumor is malignant or benign.
- `scaler.pkl`: Saved feature scaler.
- `model.pkl`: Saved trained model.
- `selected_features.pkl`: Features selected using `SelectKBest`.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/breast-cancer-prediction.git
