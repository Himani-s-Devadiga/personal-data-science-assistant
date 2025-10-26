# Personal Data Science Assistant: Smart House Price Predictor

A beginner-friendly data science project that predicts house prices and provides an interactive dashboard for exploratory analysis. Built using Python, TensorFlow, and advanced visualization libraries, this assistant helps users explore housing data and get price predictions based on multiple parameters.

---

## Features

- **House Price Prediction**: Predict house prices using a GPU-accelerated neural network.
- **Exploratory Data Analysis (EDA)**: Interactive visualizations for insights on bedrooms, bathrooms, living area, and grades.
- **Interactive Dashboard**: Filter houses by bedrooms, bathrooms, grade, square footage, and zipcode to visualize price trends.
- **GPU Support**: Detects available GPU for faster model training using TensorFlow/PyTorch.

---

## Tech Stack

- **Python**: Core programming language
- **Pandas & NumPy**: Data handling and preprocessing
- **TensorFlow**: Neural network for regression
- **Scikit-learn**: Data preprocessing and evaluation
- **Matplotlib & Seaborn**: Data visualization
- **Ipywidgets**: Interactive dashboard
- **GitHub**: Version control

---

## Dataset

- **Source**: [King County House Sales Dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction) (inside ZIP: `archive (6).zip`)
- **Features Used**: bedrooms, bathrooms, sqft_living, floors, grade, sqft_above, sqft_basement, lat, long, zipcode

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Himani-s-Devadiga/personal-data-science-assistant.git
2.Install dependencies:

pip install -r requirements.txt


3.Run the interactive dashboard:

jupyter notebook
# or
streamlit run personal_ds_assistant.py

## Screenshots
EDA Correlation Heatmap – shows feature correlations
<img width="1553" height="906" alt="Screenshot 2025-10-26 195740" src="https://github.com/user-attachments/assets/99918686-2177-4cea-816f-8c3ca312849d" />


Interactive Plots – bedrooms vs price, bathrooms vs price, grade vs price
<img width="1367" height="750" alt="Screenshot 2025-10-26 195645" src="https://github.com/user-attachments/assets/a446ca1c-e784-4280-b5e0-d554454ef249" />

Prediction Example – a sample house prediction output
<img width="1126" height="758" alt="Screenshot 2025-10-26 195655" src="https://github.com/user-attachments/assets/8ff630d4-6ef4-4e22-8c93-17cd0d1ceb6b" />


## Future Improvements:

Deploy as a web app for real-time user input.

Add more features like neighborhood amenities, school rating, and crime rate.

Use more advanced models like XGBoost or ensemble methods.
