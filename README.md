# Wildfire-Analysis-in-California

## **📌 Project Overview**
This project explores **historical wildfire patterns in California from 1984 to 2023**, using **weather and fire occurrence data**. Through **exploratory data analysis and hypothesis testing**, we aim to understand:
- 📊 **How wildfire frequency has changed over time**  
- 🌡️ **How temperature, wind speed, and precipitation influence wildfires**  
- 🛠️ **Which months are most fire-prone**  
---

## **📊 Dataset Overview**
This dataset contains **daily records** of wildfire and weather conditions, including:

| Feature | Description |
|---------|------------|
| `DATE` | Date of observation |
| `FIRE_START_DAY` | 🔥 Binary indicator (1 = Fire started, 0 = No fire) |
| `MAX_TEMP` | 🌡️ Maximum daily temperature (°F) |
| `AVG_WIND_SPEED` | 💨 Average wind speed (mph) |
| `PRECIPITATION` | ☔ Daily precipitation (inches) |
| `LAGGED_PRECIPITATION` | Previous 7-day precipitation |
| `LAGGED_AVG_WIND_SPEED` | Previous 7-day wind speed |
| `MONTH`, `YEAR`, `DAY_OF_YEAR` | Temporal indicators for trend analysis |

📌 **Source:**Yavas, C. E., Kadlec, C., kim, J., & Chen, L. (2025). California Weather and Fire Prediction Dataset (1984–2025) with Engineered Features [Data set]. Zenodo. https://doi.org/10.5281/zenodo.14712845**
---

## **📈 Key Analysis**
### ✅ **1. Wildfire Trends Over Time**
**🔥 Have wildfires become more frequent over the years?**  
This analysis examines annual and monthly wildfire trends to identify long-term changes in fire frequency.

---

### ✅ **2. Correlation Between Weather & Wildfires**
**🔍 What weather conditions drive wildfires?**  
This section analyzes **temperature, wind speed, and precipitation** to determine which factors contribute most to wildfire occurrences.

---

### ✅ **3. Hypothesis Testing: Does Temperature Affect Wildfires?**
🧪 *Testing if high temperatures significantly increase fire risk*  
We use statistical hypothesis testing to check if **hotter days are more likely to have wildfires**.

---

## **🚀 Installation & Setup**
### **🔹 Requirements**
Ensure you have **Python 3.8+** and install the required libraries:
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
```

### **🔹 Running the Analysis**
1. Clone the repository:
```bash
git clone https://github.com/leahdsouza/Wildfire-Analysis-in-California
```
2. Open **Jupyter Notebook**:
```bash
jupyter notebook
```
3. Run the **`main.ipynb`** notebook.

---

## **📂 Project Structure**
```
📂 wildfire-analysis-in-california
 ┣ 📜 main.ipynb  # Jupyter Notebook with full analysis
 ┣ 📜 wildfire_data.csv        # Dataset (not included, download separately)
 ┣ 📜 README.md                # Project documentation
 ┣ 📜 requirements.txt         # Required Python packages
```

---

## **📢 Future Enhancements**
✅ **Machine Learning:** Use **Random Forest/XGBoost** for wildfire risk prediction  
✅ **Interactive Dashboard:** Create **Power BI/Tableau visualizations**  
✅ **Geospatial Analysis:** Map wildfire-prone zones using GIS tools  
✅ **Real-Time Fire Monitoring:** Integrate **live weather data APIs**  

---
