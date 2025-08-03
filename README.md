# 🚧 Traffic Accident Data Analysis & Visualization

This project analyzes traffic accident data to identify patterns related to **road conditions**, **weather**, and **time of day**, helping to uncover the key contributing factors to accidents. It includes visualizations that highlight **accident hotspots** and offer insights to support public safety and urban planning decisions.

---

## 🎯 Objective

- Discover patterns and correlations in accident data  
- Identify high-risk **time periods**, **weather conditions**, and **road types**  
- Visualize **geographic hotspots** for traffic accidents  
- Provide actionable insights for road safety improvements

---

## 📁 Dataset

- **Source**: [e.g., US Accident Dataset from Kaggle](https://www.kaggle.com/sobhanmoosavi/us-accidents)
- **Size**: ~2.8 million records  
- **Key fields**:
  - `Start_Time`, `End_Time`
  - `Weather_Condition`
  - `Road_Surface_Condition`
  - `Severity`
  - `City`, `State`
  - `Latitude`, `Longitude`

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy)
- **Matplotlib**, **Seaborn**, **Plotly**
- **Jupyter Notebook**

---

## 🧠 Workflow

1. **Data Cleaning & Preprocessing**
   - Handle missing values
   - Convert time formats
   - Categorize weather and road conditions

2. **Exploratory Data Analysis (EDA)**
   - Accident distribution by hour, day, and month
   - Severity vs. weather and road conditions
   - State-wise and city-wise accident trends

3. **Visualization**
   - Heatmaps and bar plots for trends
   - Time series analysis
   - Geographic accident hotspots using latitude/longitude

---

## 📊 Sample Visuals

- 📈 Accidents by Hour of Day  
- ☁️ Weather Conditions vs. Severity  
- 🌍 Heatmap of Accident Locations (Folium)  
- 📅 Monthly Trend of Accidents  

<img width="1231" height="855" alt="Confusion_Matrix" src="https://github.com/user-attachments/assets/6436ba40-6dbc-4087-a080-fb62abd68a85" />


---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Sid-pr/CODECRAFT_DS_05.git
   cd traffic-accident-analysis

2. Install dependencies
   ```bash
   pip install -r requirements.txt

3. Run jupyter notebook
   ```bash
   jupyter notebook accident_analysis.ipynb
