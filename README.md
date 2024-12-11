# 🧠 Age and Gender Prediction App

This repository contains a **Streamlit** application for predicting the **age** and **gender** of a person based on an uploaded image. The app uses a **Convolutional Neural Network (CNN)** trained on the [UTKFace dataset](https://susanqq.github.io/UTKFace/) for the predictions.

---

## 📋 Features

- Predict **Gender**: Male or Female.
- Predict **Age**: Estimated age of the subject.
- **Batch Processing**: Upload multiple images and get predictions for all.
- Download predictions as a CSV file.

---

## 🚀 How It Works

1. Upload an image in `.jpg`, `.jpeg`, or `.png` format.
2. The app processes the image using the trained model.
3. Displays the predicted **age** and **gender**.
4. (Optional) Download predictions for multiple images in CSV format.

---

## 📦 Requirements

To run the application, make sure you have the following dependencies installed:

- Python 3.8 or higher
- `streamlit`
- `numpy`
- `pandas`
- `Pillow`
- `keras`

Install all dependencies using:

```bash
pip install -r requirements.txt
