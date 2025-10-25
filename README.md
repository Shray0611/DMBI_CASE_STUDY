# ✈️ Airline Price Optimization Dashboard & DSS (v3)

## 📘 Overview
A complete **Decision Support System (DSS)** and **Business Intelligence (BI) Dashboard** for an airline’s pricing team.  
It predicts ticket fares using machine learning and provides insights into seasonal trends, competitor pricing, and demand elasticity.

---

## 🎯 Key Features

### 🧠 Decision Support System (Price Predictor)
- Real-time **Dynamic Price Recommendation** using a trained ML model (`RandomForestRegressor`).
- Inputs: Airline, Route, Class, Total Stops, Departure Time, and Days Left.
- Auto-calculates **Journey Month** and **Quarter** for seasonal context.

### 📊 Business Intelligence Dashboard
- **Seasonal Trends:** Average fare by Month & Quarter.
- **Competitor Analysis:** Compare fares across Airlines & Cabin Classes.
- **Booking Patterns:** Price vs. Days Left visualization.
- **Demand Elasticity:** Economy vs. Business fare comparison.
- **Top Routes:** Top 15 most expensive flight routes.

---

## 🧰 Tech Stack
- **Language:** Python 3.8+  
- **Libraries:** Streamlit, Pandas, Scikit-learn, Altair, Joblib  
- **Model:** RandomForestRegressor (100 trees, max_depth=20)

---

## 📂 Project Structure
<img width="383" height="455" alt="image" src="https://github.com/user-attachments/assets/0255362f-7039-4949-96fb-d1c1c5828750" />


---

## ⚙️ How to Run

### 1️⃣ Install Dependencies
```bash
pip install -r v3_requirements.txt
python scripts/v2_preprocess_and_train.py
streamlit run v3_app.py


---

✅ Just copy and paste this directly — it will render perfectly on **GitHub**, **Streamlit Cloud**, or any Markdown viewer.  
Would you like me to also include a section for **screenshots or demo links** (so you can just add images later)?

