# ⚡ EV Charging Demand Forecasting Project
This project aims to forecast electric vehicle (EV) charging demand at specific stations using time-series modeling and visualization techniques. It helps optimize station usage, plan charger installations, and improve customer satisfaction by predicting usage patterns.

## 🚀 Project Overview
**Objective**: Forecast future EV charging demand at a selected station using time-series analysis (ARIMA), and provide actionable insights via interactive visualizations.

**Scope**:
- Historical demand analysis  
- Forecast modeling (ARIMA)  
- Weekly usage pattern exploration  
- Geo-location-based demand interpretation  

## 📊 Dashboard Insights

![image](https://github.com/user-attachments/assets/f181c371-f175-4c16-aa39-c71020e6f3d3)

### Key Components:
**📈 Time Series Forecast**:
- Uses ARIMA modeling to forecast future demand  
- Displays average forecast and confidence intervals  
- Shows seasonal trends and anomalies  

**📅 Weekly Usage Heatmap**:
- Reveals day-of-week usage patterns across months  
- Useful for identifying peak traffic times and days  

**🗺️ Station Location Map**:
- Maps forecasted data to the physical location (e.g., Palo Alto, CA)  
- Helpful for spatial decision-making and expansion planning  

## 📂 Project Structure

```plaintext
EV-Charging-Demand-Forecasting/
│
├── electric vechile charging demand forecasting zip(datasets)/
│   └── ev_station_usage.csv            # Cleaned and processed historical usage data
│   └── weather_traffic_data.csv        # Optional contextual features
│   └── EvChargingStationUsage.csv
│
├── jupyter notebooks/
│   └── Data_Preprocessing & EDA.ipynb                       # Exploratory Data Analysis
│   └── ARIMA_Modeling & prophet model.ipynb                # Time series modeling and evaluation
│   └── Timesries and Generated final Forcasted file
│
├── ev tableau/
│   └── forecasts.csv                   # Final forecast results
│   └── dashboard.twbx                  # Tableau workbook/dashboard
│
├── EV Charging Demand Insights.png     # Final dashboard image
├── README.md
└── requirements.txt                    # Python dependencies
🔧 Technologies Used
Python (pandas, numpy, matplotlib, statsmodels)

Time-Series Modeling: ARIMA

Visualization: Tableau (for the interactive dashboard)

Geospatial Mapping: Mapbox via Tableau

Optional Data Sources: Weather APIs, traffic volume feeds (if integrated)

📈 Forecasting Approach
Used ARIMA (Auto-Regressive Integrated Moving Average) due to strong seasonality and trend in EV charging behavior.

Evaluated models based on RMSE, MAE, and visual forecast accuracy.

Added contextual overlays like confidence intervals for demand spikes.

🧠 Insights & Recommendations
Consistent peak usage on weekends and mid-month weekdays

Demand gradually increases over time, suggesting growth in EV adoption

Strategic recommendation: Add more charging units during weekends and holiday seasons

Station at Palo Alto CA / Hamilton #1 shows significant upward trend — suitable for scaling

🔍 Future Work
Incorporate weather, traffic, and event data into the forecasting model

Deploy real-time dashboards using Power BI or Tableau Public

Implement optimization models to guide infrastructure expansion (e.g., linear programming for charger allocation)


