# 🎬 Movie Box Office Revenue Prediction

> Predicting domestic box office revenue using **Machine Learning (Linear Regression)** and data preprocessing techniques in Python.

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-green?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

</p>

---

# 📖 Overview

Movie Box Office Revenue Prediction is a machine learning project that predicts the **domestic box office revenue** of a movie based on several key attributes, including:

- 🎭 Movie genres
- 🎬 Distributor
- 🔞 MPAA rating
- 🏢 Number of opening theaters

The project applies a complete machine learning workflow, from data preprocessing and feature engineering to model training, evaluation, visualization, and prediction for new movies.

---

# ✨ Features

- 📊 Data Cleaning & Preprocessing
- 🔢 Feature Engineering
- 🏷 Label Encoding
- 🎭 Genre Vectorization using CountVectorizer
- 📈 Data Visualization
- 🤖 Linear Regression Model
- 📉 Model Evaluation
- 🎬 Predict Revenue for New Movies
- 📊 Interactive Prediction Visualization

---

# 🏗 Project Workflow

```text
Dataset

↓

Data Cleaning

↓

Missing Value Handling

↓

Feature Engineering

↓

Label Encoding

↓

Genre Vectorization

↓

Feature Scaling

↓

Train/Test Split

↓

Linear Regression

↓

Model Evaluation

↓

Revenue Prediction

↓

Visualization
```

---

# 📂 Project Structure

```text
Movie-BoxOffice-Revenue-Prediction/

│

├── boxoffice.csv

├── boxrevenueprediction.ipynb

├── boxrevenueprediction.py

├── README.md

└── images/
```

---

# 🚀 Technologies Used

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Data Analysis | Pandas |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Statistical Visualization | Seaborn |

---

# 📊 Data Preprocessing

The dataset undergoes several preprocessing steps:

- Remove unnecessary columns
- Handle missing values
- Convert revenue values to numeric format
- Remove invalid records
- Apply logarithmic transformation
- Encode categorical variables
- Vectorize movie genres
- Standardize numerical features

---

# 🤖 Machine Learning Model

Algorithm:

```
Linear Regression
```

Feature Engineering includes:

- Label Encoding
- CountVectorizer
- StandardScaler
- Log Transformation

---

# 📈 Model Evaluation

The model is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Example output:

```text
MAE  = 0.308

RMSE = 0.416

R²   = -0.0139
```

---

# 📊 Visualizations

The project generates multiple visualizations including:

- MPAA Distribution
- Opening Theaters Distribution
- Revenue Distribution
- Correlation Heatmap
- Actual vs Predicted Revenue
- Revenue Boxplot
- Genre Pie Chart
- Opening Theaters vs Revenue

---

# 🎬 Predict a New Movie

Users can input:

- MPAA Rating
- Distributor
- Opening Theaters
- Movie Genres

Example:

```text
MPAA: PG-13

Opening Theaters: 3500

Genres:
Action Adventure Sci-Fi
```

Predicted Output:

```text
Predicted Domestic Revenue

$84,532,671.45
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/cuongle010205/BOX-REVENUE-PREDICTION.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python boxrevenueprediction.py
```

or

```bash
jupyter notebook
```

---

# 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
```

Install all packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

# 📸 Project Screenshots

Suggested screenshots for the repository:

- Dataset Preview
- Correlation Heatmap
- Revenue Distribution
- Actual vs Predicted Scatter Plot
- Revenue Prediction Result

---

# 🔮 Future Improvements

- Implement Random Forest Regression
- Add XGBoost Regression
- Hyperparameter Optimization
- Feature Selection
- Cross Validation
- Web Deployment using Streamlit
- REST API with FastAPI
- Model Persistence using Joblib

---

# 👨‍💻 Author

**Lê Long Cương**

🎓 University of Science – VNUHCM

💡 Interested in Artificial Intelligence, Machine Learning, and Software Engineering.

GitHub:
https://github.com/cuongle010205

LinkedIn:
www.linkedin.com/in/cươnglê-991b01402

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
