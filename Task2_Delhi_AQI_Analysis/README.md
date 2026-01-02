Delhi AQI Analysis 📊
Welcome to my exploratory analysis of Delhi's air quality! This project digs into hourly air quality data to uncover pollution patterns, pinpoint the worst days and hours, and explore how different pollutants interact.

📋 What's Inside
Dataset: Hourly measurements of PM2.5, PM10, NO₂, SO₂, CO, O₃, and NH₃

Main Goals:

Find the most polluted dates and peak hours

Understand daily and hourly pollution patterns

Study relationships between pollutants

Provide actionable insights for health and policy

🔧 What I Did
Cleaned the data and created time-based features (hour, day, etc.)

Built a simple AQI proxy using PM2.5 + PM10 averages

Identified peaks: Worst single hour, worst days, and typical dirty hours

Visualized patterns with time series, boxplots, and correlation heatmaps

Categorized air quality into Good/Poor/Severe bands

📈 Key Findings
Worst hour: Specific timestamp with extreme PM2.5/PM10

Worst days: Top dates by daily average pollution

Peak time: Late afternoon (around 5 PM) typically most polluted

Dominant pollutants: PM2.5 & PM10 lead the way

🛠️ Tools Used
Python + Pandas for data handling

Matplotlib + Seaborn for visualizations

Jupyter Notebook for the full analysis

📁 Files
delhiaqi.csv – Raw hourly air quality data

delhi_aqi_analysis.ipynb – Complete notebook with code + visuals

🎯 Next Steps
Add weather data for better context

Compare seasons (if more data available)

Implement official AQI calculation formula
