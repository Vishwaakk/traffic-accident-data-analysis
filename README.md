🚦 Traffic Accident Data Analysis
📌 Project Overview
This project analyzes the US Traffic Accidents dataset to identify patterns related to:

Time of day
Weather conditions
Road environment
Accident severity
The goal is to discover accident hotspots and understand the key contributing factors behind crashes using data analysis and visualization.

📂 Dataset
Dataset source: Kaggle – US Accidents Dataset
Contains millions of accident records with:

Date & time
Location (latitude/longitude)
Weather conditions
Road features
Severity levels
For performance, 200,000 records were sampled for analysis.

🛠 Tools Used
Python
Pandas
Matplotlib
Seaborn
Folium (for heatmaps)
VS Code / Jupyter Notebook
📊 Analysis Performed
✔ Data cleaning and preprocessing
✔ Time-based accident analysis (hour, day periods)
✔ Weather impact analysis
✔ Severity distribution study
✔ Weather vs Severity correlation
✔ Geographic hotspot visualization using heatmaps

📈 Key Insights
Most accidents occur during evening rush hours (4 PM – 8 PM)
Afternoon and evening periods show the highest crash frequency
Rain, fog, and poor weather increase accident risk
Majority of cases fall under moderate severity levels (2–3)
Accidents cluster around urban areas and highways
Combined factors like bad weather + traffic + low visibility increase severity
🗺 Visual Outputs
All visualizations are saved inside the outputs/ folder:

accidents_by_hour.png
time_period_distribution.png
weather_conditions.png
severity_distribution.png
weather_vs_severity.png
accident_hotspots.html (interactive map)
▶ How to Run
Place dataset CSV inside project folder
Open analysis.ipynb in VS Code
Run all cells
Or using Python:

python main.py# traffic-accident-data-analysis
