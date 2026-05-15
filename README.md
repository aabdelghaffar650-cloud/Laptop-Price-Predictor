# Laptop Price Predictor 💻

This project is a Machine Learning solution designed to predict laptop prices based on technical specifications. It includes a complete data science workflow, from data cleaning and Exploratory Data Analysis (EDA) to model deployment using a Pipeline.

## 🚀 Features
* **Data Processing:** Handling missing values and cleaning technical specs (RAM, Weight, etc.).
* **Pipeline Architecture:** Uses Scikit-Learn's `Pipeline` for seamless transformation and prediction.
* **Regression Model:** Predicts price based on brand, type, processor, and more.

## 📂 Project Structure
* `laptop_price_prediction.ipynb`: The main notebook containing EDA and model training.
* `laptopData.csv`: The dataset used for training and testing.
* `pipe.pkl`: The serialized Scikit-Learn pipeline (ready for deployment).
* `df.pkl`: Processed dataframe for use in web applications (like Streamlit).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn.

## 📊 Results
The model was trained and evaluated using log-transformation for price to handle skewness, achieving solid performance on the test set.
