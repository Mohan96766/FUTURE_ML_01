# Superstore Sales Forecasting – Task 01

**Built with Python & Time-Series Analysis (Prophet)**  
This project forecasts monthly sales for a Superstore using historical data and predicts future trends for business planning.

---

## 📝 Business Problem
Retail managers need to predict sales to:  
- Plan inventory and resources efficiently  
- Identify seasonal peaks and dips  
- Make informed marketing and staffing decisions  
- Reduce understocking or overstocking losses

---

## ⚙️ Features
- Aggregate sales data to monthly totals  
- Handle missing or inconsistent values  
- Time-series forecasting using Prophet  
- Include trend, yearly seasonality, and holiday effects  
- Predict next 12 months of sales  
- Visualizations:
  - Historical + Forecasted Monthly Sales  
  - Forecast Components (trend, seasonality, holidays)  
  - Last 12 months actual vs forecast with confidence intervals

---

## 🛠 Tools & Libraries
- **Python 3**  
- **Jupyter Notebook**  
- **Libraries**: pandas, numpy, matplotlib, seaborn, prophet  

---

## 📊 How it Works
1. Clean and aggregate sales data into monthly totals.  
2. Prepare data in Prophet format (`ds` = date, `y` = sales).  
3. Fit Prophet model with yearly seasonality and holidays.  
4. Forecast sales for the next 12 months.  
5. Visualize forecast and components for trend and seasonality insights.  
6. Compare recent actual sales with forecast using confidence intervals.

---

## 🖼 Screenshots / Visualizations

### Historical + Forecasted Sales
![Monthly Sales Forecast](main/Monthly_sales_forecast.png.png
)


### Forecast Components (Trend, Seasonality, Holidays)
![Forecast Components](main/Forecast_components.png)

### Recent 12-Month Actual vs Forecast
![Recent Sales Forecast](main/Recent_sales_forecast.png)

---

## 📂 Repository Structure


