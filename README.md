# 🌧️ Cloudburst Prediction

This project aims to **predict cloudbursts** using machine learning and deep learning models. Accurate cloudburst prediction can help in disaster management, early warning systems, and preventing loss of life and property.
The given csv file is free of null values and outliers.

## 🚀 Models Used
- **Random Forest** – for feature-based classical prediction
- **Artificial Neural Network (ANN)** – for pattern-based prediction
- **Long Short-Term Memory (LSTM)** – for temporal pattern recognition and sequence prediction

## 📂 Project Structure
- `ann_model.ipynb` – ANN implementation
- `lstm_model.ipynb` – LSTM implementation
- `random_forest.ipynb` – Random Forest model
- `requirements.txt` – Python dependencies
- `README.md` – Project documentation

## 🛠️ Technologies & Libraries
- Python 3.x
- Pandas, NumPy, Scikit-learn
- TensorFlow / Keras
- Matplotlib, Seaborn
- XGBoost

## ✅ How to Run
1. Clone the repository  
   `git clone https://github.com/your-username/cloudburst-prediction.git`
2. Navigate into the folder  
   `cd cloudburst-prediction`
3. Install dependencies  
   `pip install -r requirements.txt`
4. Open the notebooks and run each cell step-by-step.

## 💡 Motivation
Cloudbursts cause flash floods and pose major risks in mountainous and high-rainfall areas. We aim to build a model that uses meteorological data to provide accurate early predictions.

## 📌 Judging Criteria Met
- ✔️ Innovation through hybrid ML/DL models  
- ✔️ Social good: Natural disaster mitigation  
- ✔️ Technical complexity (LSTM + ANN + RF)  
- ✔️ Ready for real-world application

RESULT:
ANN RESULT
              precision    recall  f1-score   support

           0       0.87      0.95      0.91     22672
           1       0.74      0.50      0.59      6420

    accuracy                           0.85     29092
   macro avg       0.81      0.72      0.75     29092
weighted avg       0.84      0.85      0.84     29092
