# 🚢 Mini-Project 1 – Detecting Anomalous Activity in Ship Engines

> Data Science Mini-Project | Synthetic Data

---

## 💡 Project Overview

This mini-project analyzes **simulated ship engine sensor data** to detect anomalies that could indicate potential mechanical failures. Early detection of these anomalies helps reduce costly downtime and improves predictive maintenance in the maritime industry.

**Key techniques used:**
- Exploratory Data Analysis (EDA)
- Outlier detection with:
  - Interquartile Range (IQR)
  - One-Class SVM
  - Isolation Forest
- Dimensionality reduction with PCA
- Data visualization with Matplotlib and Seaborn

---

## 📂 Project Files

- `Ortuno_Alejandro_CAM_C101_W5_Mini-project.ipynb` → Jupyter notebook with full analysis and modeling.

---

## 🔎 Project Steps

1. **Data Exploration**
   - Analyzed distributions and correlations in sensor data.
   - Identified initial signs of anomalies.

2. **Dimensionality Reduction**
   - Applied Principal Component Analysis (PCA) to visualize high-dimensional data.

3. **Anomaly Detection**
   - Used IQR method to detect outliers in key features.
   - Trained One-Class SVM and Isolation Forest models.
   - Compared results and visualized anomalies.

4. **Visualization**
   - Plotted PCA results to identify potential clusters of anomalies.
   - Created scatter plots and heatmaps to interpret model outputs.

---

## 📊 Key Insights

- Models successfully detected abnormal readings in temperature and vibration sensors, suggesting potential engine issues.
- PCA visualizations helped reduce dimensions from 10 to 2 while retaining ~90% of variance.

---

## 🚫 Confidentiality Note

> This project uses **synthetic data only** and does **not contain any proprietary or confidential information.** It’s safe to include in a public portfolio.

---

## 🛠️ Technologies Used

- Python 3.9
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 👨‍💻 Author

Alejandro Ortuño  
[LinkedIn](www.linkedin.com/in/alejandro-ortuno-garcia-1bb778171) | [GitHub](https://github.com/aleorgar)
