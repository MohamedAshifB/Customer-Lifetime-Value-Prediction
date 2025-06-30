# Customer-Lifetime-Value-Prediction

This project predicts Customer Lifetime Value (CLV) based on transactional data from an online retail dataset. By building a regression model and segmenting customers into value tiers, it provides actionable insights for targeted marketing and customer retention strategies.


## 📌 Project Objective

Estimate the total expected revenue from each customer to:
- Identify high-value customers
- Optimize marketing spend
- Improve customer retention

## 🛠️ Tools & Technologies

- **Python**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Jupyter Notebook**
- **Excel**: Data source
- **GitHub**: Project hosting

## 📂 Files Included

- `CLV_Prediction_Notebook.ipynb` – Jupyter notebook with all preprocessing, modeling, and predictions.
- `final_clv_predictions.csv` – Final output with each customer’s predicted CLV and segment.
- `CLV_Project_Report.pdf` – 1–2 page report as required by the internship.

## 🔎 Project Steps

1. Loaded and cleaned transactional data (removing missing customer IDs).
2. Engineered RFM features:
   - **Recency**: Days since last purchase
   - **Frequency**: Number of transactions
   - **Monetary/AOV**: Average Order Value
3. Built a Random Forest regression model to predict CLV.
4. Evaluated the model with MAE and RMSE metrics.
5. Predicted CLV for all customers and segmented them into:
   - Low
   - Mid-Low
   - Mid-High
   - High
6. Saved predictions and segments to `final_clv_predictions.csv`.

## 📊 Deliverables

- Jupyter notebook with full pipeline
- Final predictions CSV file
- Project report PDF

## ✅ Conclusion

This project demonstrates an end-to-end CLV prediction pipeline, enabling businesses to identify and target their most valuable customers effectively.

---
