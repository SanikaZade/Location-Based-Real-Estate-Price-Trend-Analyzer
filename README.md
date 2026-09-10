# 🏡 Location-Based Real Estate Price Trend Analyzer

A machine learning project that predicts real estate prices using property features and visualizes property locations on an interactive map.
The goal of this project is to help users understand property price trends across different locations by combining data preprocessing, machine learning, and geographic visualization.

---

## 📌 Project Overview

Buying or investing in real estate often requires comparing prices across multiple locations. This project simplifies that process by analyzing housing data, predicting property prices using Machine Learning, and displaying property locations on a map.

The project mainly focuses on:

- Cleaning and preparing housing data
- Building a price prediction model
- Visualizing properties geographically
- Understanding location-wise price trends

---

## ✨ Features

- Property price prediction using Machine Learning
- Data preprocessing and feature engineering
- Categorical feature encoding
- Interactive map visualization
- JSON data generation for map display
- Easy-to-understand project workflow

---

## 🛠️ Tech Stack

### Programming Languages
- Python
- JavaScript

### Libraries
- Pandas
- NumPy
- Scikit-learn
- OpenPyXL
- Xlsx (Node.js)

### Visualization
- Google Maps API

---

## 📂 Project Structure

```
Real-Estate/
│
├── CODE_ML_minor.ipynb              # Machine Learning model
├── preprocess data final code.ipynb # Data preprocessing
├── Original Housing data.xlsx       # Raw dataset
├── final_dataset.xlsx               # Processed dataset
├── map show.xlsx                    # Dataset for map
├── data.json
├── data_with_latlng.json
├── excel_to_json.js
├── geocode_to_latlng.js
├── index.html                       # Interactive map
├── package.json
└── README.md

```
---

## 🗺️ Final interface 
<img width="1407" height="916" alt="Screenshot 2026-03-28 122644" src="https://github.com/user-attachments/assets/17238dd0-7131-4c72-b139-0da93b546b7b" />

---

## 📊 Machine Learning Workflow

```
Housing Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Encoding Categorical Features
        │
        ▼
Train-Test Split
        │
        ▼
Linear Regression Model
        │
        ▼
Price Prediction
        │
        ▼
Performance Evaluation
```

---

## 📈 Features Used

The prediction model uses several property attributes, including:

- Location
- Property Type
- Area Type
- Price per Square Foot
- Property Category (Ribbon)
- Other encoded property features

---

## 🗺️ Map Visualization

The project includes a simple web page that displays property locations on Google Maps.

Each marker provides information such as:

- Property location
- Price per square foot

The map uses latitude and longitude values stored in `data_with_latlng.json`.

---

##  How to Run

### Clone the repository

```bash
git clone https://github.com/SanikaZade/Real-Estate-.git
```

### Install dependencies

```bash
npm install
```

### Run the notebooks

Open the notebooks using Jupyter Notebook or Google Colab.

```
preprocess data final code.ipynb
CODE_ML_minor.ipynb
```

### Launch the map

Open

```
index.html
```

in your browser.

---

## 📁 Dataset

The project includes:

- Original housing dataset
- Cleaned dataset
- Dataset prepared for map visualization

These datasets are used for preprocessing, model training, and geographic visualization.

---

## 📊 Model

The project uses **Linear Regression** for property price prediction.

The model is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 💡 Future Improvements

- Add more property data from multiple cities
- Try advanced regression models such as Random Forest and XGBoost
- Build a Flask or Streamlit web application
- Add filters based on budget, location, and property type
- Improve prediction accuracy with additional features


---

