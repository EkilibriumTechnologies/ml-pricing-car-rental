# ml-pricing-car-rental
# 🚙 ML Project: Suggested Rental Pricing Model

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EkilibriumTechnologies/ml-pricing-car-rental/blob/main/precios%20sugeridos%20usando%20diarios.ipynb)

This project applies **Machine Learning** to predict and suggest optimal daily rental prices for Jeep vehicles in Puerto Rico.  
It leverages historical reservation data, business rules, and seasonality to generate **data-driven pricing recommendations**.

---

## 📌 Project Overview
- **Data Source**: Historical rental reservations (Excel exports).  
- **Goal**: Build a pricing model that:
  1. Cleans and preprocesses raw reservation data.  
  2. Aggregates results by month and vehicle class.  
  3. Trains a regression model (HuberRegressor).  
  4. Predicts prices for future months.  
  5. Applies business rules (floors, ceilings, weekend/holiday uplifts).  
  6. Outputs **suggested rental prices**.  

---

## 🛠 Tech Stack
- Python (pandas, numpy, matplotlib, scikit-learn)  
- Google Colab  
- holidays (US & PR calendar)  

---

## 📂 Repository Structure
ml-pricing-car-rental/
│── precios_sugeridos_usando_diarios.ipynb # Main notebook
│── requirements.txt # Dependencies
│── .gitignore # Ignore datasets & temp files
│── README.md # Project documentation

---

## ⚙️ Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/EkilibriumTechnologies/ml-pricing-car-rental.git
cd ml-pricing-car-rental
pip install -r requirements.txt



## 📊 Results

Model trained with HuberRegressor

Predictions generated for the upcoming months

Suggested prices adjusted for seasonality, fleet size, and holidays

## 👤 Author

Llarod Hernaiz
Data & AI Consultant – LinkedIn

Founder of Ekilibrium Technologies

