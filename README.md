# Airbnb Price Prediction

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)

A machine learning project predicting Airbnb prices using regression models (Linear, Ridge, ElasticNet, XGBoost).

---

## 📋 Overview

This project predicts Airbnb listing prices based on features such as location, room type, minimum nights, and more, using multiple regression models. Accurate price prediction helps Airbnb hosts optimize their pricing strategy, and assists guests in identifying fair deals.

---

## 🏆 Model Metrics

| Model                 | RMSE   | R² Score |
|-----------------------|--------|----------|
| Linear Regression     | 0.4033 | 0.6703   |
| Ridge Regression      | 0.4033 | 0.6704   |
| ElasticNet Regression | 0.4074 | 0.6636   |
| XGBoost Regression    | 0.3727 | 0.7185   |

---

## 📊 Dataset

- **Location:** city, latitude, longitude
- **Property:** property type, room type
- **Booking:** minimum nights, availability
- **Reviews:** number of reviews
- **Target:** price (per night)

(Dataset source: _add link or name here if public_)

---

## 🤖 Models Used

- **Linear Regression:** Baseline model for comparison.
- **Ridge Regression:** Handles multicollinearity with L2 regularization.
- **ElasticNet Regression:** Combines L1 and L2 regularization for feature selection.
- **XGBoost Regression:** Powerful ensemble model for non-linear relationships.

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Amanyadav-07/Airbnb-Price-Prediction.git
   cd Airbnb-Price-Prediction
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Open and run the main notebook:**
   ```bash
   jupyter notebook Airbnb_Price_Prediction.ipynb
   ```
   Or [view it on GitHub](./Airbnb_Price_Prediction.ipynb).

   _Adjust data paths and parameters in the notebook as needed._

---

## 📁 Project Structure

```
Airbnb-Price-Prediction/
├── .gitignore
├── Airbnb_Price_Prediction.ipynb
├── Airbnb_Price_Prediction.pdf
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 👤 Author

**Aman Kumar Yadav**  
[GitHub Profile](https://github.com/Amanyadav-07)