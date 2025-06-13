# 🏠 Boston House Price Prediction Web App

This project is a **Machine Learning web application** that predicts the **house prices in Boston** based on user-input features. It leverages a trained regression model and is deployed using **Flask** for a seamless web interface experience.



## 🚀 Features

- 🔢 Predict house prices using 13 key features.
- 💡 Clean and responsive frontend built with HTML5 + CSS3.
- 🧠 Trained ML model using Scikit-learn (Linear Regression/Decision Tree/Random Forest).
- 🧪 Tested on Boston Housing Dataset (from `sklearn.datasets`).
- 🌐 Backend powered by Flask.



## 📊 Input Features

The user inputs the following attributes:

- `CRIM` — Per capita crime rate by town
- `ZN` — Proportion of residential land zoned for lots over 25,000 sq.ft.
- `INDUS` — Proportion of non-retail business acres per town
- `CHAS` — Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- `NOX` — Nitric oxides concentration (parts per 10 million)
- `RM` — Average number of rooms per dwelling
- `AGE` — Proportion of owner-occupied units built prior to 1940
- `DIS` — Weighted distances to five Boston employment centers
- `RAD` — Index of accessibility to radial highways
- `TAX` — Full-value property-tax rate per $10,000
- `PTRATIO` — Pupil-teacher ratio by town
- `B` — 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents
- `LSTAT` — % lower status of the population



## 📁 Project Structure

```bash
.
├── static/
│   └── styles.css          # Custom CSS (optional)
├── templates/
│   └── index.html          # Main HTML form
├── model.pkl               # Pre-trained machine learning model
├── app.py                  # Flask application
├── README.md
└── requirements.txt        # List of Python dependencies


🧰 Tech Stack
Python

Flask

Scikit-learn

HTML5/CSS3


⚙️ How to Run Locally
1.Clone the repository:
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
2.Install dependencies:
pip install -r requirements.txt
3.Run the Flask server:
python app.py
4.Open in browser:
http://127.0.0.1:5000

📜 License This project is licensed under the MIT License - see the LICENSE file for details. (If you haven't created a https://www.google.com/search?q=LICENSE file, you should! GitHub has a built-in tool to add one when you create a repo.)


