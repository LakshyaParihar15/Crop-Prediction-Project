# 🌾 Crop Prediction Project
A machine learning-based web application designed to recommend the most suitable crop for cultivation based on specific soil and environmental parameters. This tool aims to assist farmers and agricultural enthusiasts in making informed decisions to optimize yield and resource utilization.

---

## 🔗 Live Demo
Access the deployed application here:
👉 [Crop Prediction Web App](https://crop-predication-lgkr.onrender.com)

---

## 🚀 Features
- **User-Friendly Interface**: Input soil and environmental parameters through a simple web form.
- **Real-Time Predictions**: Receive immediate crop recommendations based on input data.
- **Machine Learning Model**: Utilizes a trained model to predict the best-suited crop.
- **Web Deployment**: Built with Flask, HTML, and CSS for seamless web integration.

---

## 📥 Input Parameters

Users are required to input the following features:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH
- Rainfall (mm)

These inputs are then passed through a trained model which returns the most suitable crop for the given conditions.

---

## 📊 Dataset
The dataset used for training is `Crop_recommendation.csv`, which contains:

- **Features**: N, P, K, temperature, humidity, pH, rainfall
- **Target**: Crop name

📌 **Source**: [Kaggle - Crop Recommendation Dataset](https://www.kaggle.com/datasets/aksahaha/crop-recommendation)

---

## 🤖 Model Training (Optional)

If you'd like to retrain the machine learning model using the dataset:

```bash```
python "Crop Recommendation.py"

This script will generate a new model.pkl file based on the training data.

---

## 🧰 Requirements
- Python 3.x
- Flask
- scikit-learn
- pandas
- numpy

All dependencies are listed in the requirements.txt file.

---

## 🙌 Acknowledgements
Inspired by the need to integrate machine learning into agriculture for better decision-making.

Dataset sourced from Kaggle.

---

## 📬 Contact
GitHub: [@LakshyaParihar15](https://github.com/LakshyaParihar15)

Live App: https://crop-predication-lgkr.onrender.com
