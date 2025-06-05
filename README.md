# Machine Learning Project 
# 📈 Pakistan Exports Forecasting (2005–2029) using Facebook Prophet

This project leverages **predictive analytics** to forecast **Pakistan's monthly export values** to various countries over the next 5 years (2025–2029). Using historical data from the **State Bank of Pakistan (2003–2024)**, we implemented **Facebook Prophet**, a powerful time series forecasting tool developed by Meta, to make accurate predictions and identify export trends.

---

## 🧠 Project Goals

- Clean and prepare historical export data (~56,000+ records)
- Analyze trends, seasonality, and top trading countries
- Build predictive models for top 10 export destinations
- Visualize future export forecasts and performance
- Evaluate model accuracy using MAE, RMSE, and MAPE

---

## 📊 Key Results

| Metric | Value        |
|--------|--------------|
| MAE    | 0.0208       |
| RMSE   | 0.0274       |
| MAPE   | **19.8%**    |

- ✅ **Best performance**: U.K.
- ⚠️ **Least accurate**: Afghanistan (unstable patterns)
- 🔁 Prophet handled seasonality, outliers, and missing data well

---

## 📁 Files Included

| File                          | Description |
|-------------------------------|-------------|
| `Model.ipynb` *(or `Model (2).ipynb`)* | Main notebook with data prep, modeling, visualizations |
| `dataset.csv`                | Raw monthly export data from SBP |
| `prophet_model_accuracy.csv` | Model performance metrics (MAE, RMSE, MAPE) |
| `export_forecast_dashboard_with_trend.png` | Combined forecast dashboard for top 10 countries |
| `ML model Notebook.pdf`      | Static PDF version of the notebook (optional read-only)

---

## 📍 Tools & Technologies

- Python (Jupyter Notebook)
- [Facebook Prophet](https://facebook.github.io/prophet/)
- Pandas, NumPy
- Seaborn, Matplotlib
- Time series forecasting, data cleaning, EDA

---

## 🌍 Use Case

This type of forecasting can assist:
- **Economists** in trade analysis
- **Policy makers** in future planning
- **Businesses** in export strategy alignment

---

## 📷 Snapshot

![Export Forecast Dashboard](export_forecast_dashboard_with_trend.png)

---

## 📬 Let's Connect

I'm always open to feedback, suggestions, or collaboration!

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/muhammad-umair-925508236/)  
📧 Email: your.email@example.com

---

## ⭐ If you find this project useful...
Please consider **starring** ⭐ the repo or **sharing** it with others in the field!

