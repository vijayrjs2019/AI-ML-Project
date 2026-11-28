# 🏠 Room Type Predictor – NYC Airbnb

Welcome to my **Room Type Predictor – NYC Airbnb** Machine Learning project. This project focuses on analyzing New York City Airbnb listing data and predicting room types using Machine Learning classification techniques.

The goal is to explore Airbnb listing patterns, understand important factors affecting room types, and develop a data-driven prediction system using Python.

## 📌 Project Overview

**Room Type Predictor – NYC Airbnb** is a Machine Learning classification project that analyzes Airbnb property listings in New York City to predict the room type based on various property and listing-related features.

The project uses data preprocessing, Exploratory Data Analysis (EDA), feature engineering, and classification algorithms to build an effective room type prediction model.

## 🚀 Key Features

1. 🏠 **Room Type Prediction** — Predict Airbnb room categories using Machine Learning classification algorithms.
2. 📊 **Exploratory Data Analysis (EDA)** — Analyze NYC Airbnb listing data using Pandas, Matplotlib, and Seaborn.
3. 🧹 **Data Preprocessing** — Handle missing values, duplicate records, outliers, and inconsistent data.
4. 📍 **Location Analysis** — Analyze listings based on neighbourhood groups and neighbourhoods across New York City.
5. 💰 **Price Analysis** — Explore pricing distributions and identify patterns in Airbnb listing prices.
6. 🔍 **Feature Engineering** — Prepare relevant features such as neighbourhood group, neighbourhood, price, minimum nights, availability, and reviews.
7. 🤖 **Machine Learning Models** — Implement classification algorithms such as Logistic Regression, Decision Tree, Random Forest, KNN, and SVM.
8. ⚙️ **Model Training & Testing** — Split the dataset into training and testing sets.
9. 📈 **Model Evaluation** — Evaluate model performance using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
10. 🎯 **Prediction System** — Predict room types based on user-provided Airbnb listing information.
11. 🚀 **Hyperparameter Tuning** — Optimize model performance using Cross Validation and GridSearchCV.
12. 📦 **Model Deployment** — Save and reuse the trained Machine Learning model for predictions.

## 🏷️ Prediction Categories

The model predicts the following Airbnb room types:

- Entire home/apt
- Private room
- Shared room

## 📊 Dataset Information

The project uses the **New York City Airbnb Open Data** dataset.

Important dataset features include:

- `id` — Unique listing identifier.
- `name` — Airbnb listing name.
- `host_id` — Unique host identifier.
- `neighbourhood_group` — NYC borough (Manhattan, Brooklyn, Queens, Bronx, Staten Island).
- `neighbourhood` — Specific neighbourhood.
- `latitude` — Property latitude.
- `longitude` — Property longitude.
- `room_type` — Airbnb room category (target variable).
- `price` — Nightly listing price.
- `minimum_nights` — Minimum nights required for booking.
- `number_of_reviews` — Total number of reviews.
- `reviews_per_month` — Average monthly reviews.
- `calculated_host_listings_count` — Number of listings managed by the host.
- `availability_365` — Number of available days per year.

## 🛠️ Technologies & Tools

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Google Colab
- Streamlit (if used for the prediction interface)

## 🧠 Machine Learning Concepts Covered

### 1. Data Analysis & Preprocessing
- Data Cleaning