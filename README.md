# Historical Weather Data Analysis & Insights Pipeline

An end-to-end Python data analysis project utilizing **Pandas, NumPy, and Matplotlib** to clean, aggregate, visualize, and extract insights from historical climate records.

## 🚀 Features & Workflow
- **Data Cleaning:** Processed missing/null fields and converted dates into optimized `datetime64` structures.
- **Descriptive Statistics:** Extracted key central tendency and dispersion metrics (Mean, Median, Standard Deviation) using `df.describe()` for temperature, humidity, and precipitation.
- **Time-Series Aggregation:** Grouped climate metrics using Pandas `groupby` to track monthly averages and seasonal baseline shifts.
- **Data Visualization:** Built distribution histograms, trend lines, and total rainfall bar charts to isolate climate patterns.
- **Anomaly Detection:** Engineered statistical outlier tracking via 95th-percentile thresholds to surface extreme weather events.

## 🛠️ Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib

## 📊 Key Findings
- **Seasonal Trends:** Successfully identified monthly baseline changes for temperature and precipitation across dataset seasons.
- **Extreme Events:** Successfully isolated and ranked the top 5% historical anomalies for extreme temperatures and precipitation spikes.

