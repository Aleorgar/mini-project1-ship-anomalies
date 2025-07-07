# 🚢 Mini-Project 1 – Detecting Anomalous Activity in Ship Engines

> Data Science Mini-Project | Synthetic Data

---

## 💡 Project Overview

This mini-project analyzes **synthetic ship engine sensor data** to detect anomalies that could indicate potential mechanical failures. Early detection of such anomalies helps reduce costly downtime and improves predictive maintenance in marine operations.

The analysis combines classic statistical methods and machine learning algorithms to identify outliers and visualize their patterns in lower-dimensional space.

---

## 📂 Project Files

- `Ortuno_Alejandro_CAM_C101_W5_Mini-project.ipynb` → Jupyter notebook with full analysis, modeling, and visualizations.

---

## 🔎 Project Steps

1. **Data Exploration & Cleaning**
   - Reviewed distributions and correlations among engine variables.
   - Variables included:
     - Engine rpm
     - Lub oil pressure
     - Fuel pressure
     - Coolant pressure
     - Lub oil temperature
     - Coolant temperature

2. **Outlier Detection with IQR**
   - Computed upper and lower bounds for each variable using the Interquartile Range (IQR) method.
   - Flagged data points outside these ranges as potential outliers.

3. **Dimensionality Reduction**
   - Applied Principal Component Analysis (PCA) to reduce the feature space to two principal components (PC1 and PC2).
   - Used PCA plots to visualize clusters and separate anomalies from normal readings.

4. **Anomaly Detection Models**
   - **One-Class SVM**
     - Trained with different values of `nu` (between 1% and 5%) to detect rare anomalies.
     - Required feature scaling for proper functioning.
   - **Isolation Forest**
     - Applied directly to raw data without scaling.
     - Detected similar proportions of anomalies as One-Class SVM.
     - Produced clear PCA visualizations showing separated anomaly clusters.

---

## 📊 Key Insights

- All methods detected approximately **4.9% to 5%** of data points as anomalies.
- PCA visualizations effectively separated anomalous points, helping to interpret model outputs.
- **Isolation Forest** appeared more robust on non-scaled data compared to One-Class SVM, which required careful tuning and scaling.
- The IQR method detected outliers in variables like **coolant temperature** and **lub oil temperature**, though not all matched machine learning model outputs.

---

## 🚫 Confidentiality Note

> This project uses **synthetic data only** and does **not contain any proprietary or confidential information.**  
> Safe to include in public portfolios.

---

## 🛠️ Technologies Used

- Python 3.9
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 👨‍💻 Author

Alejandro Ortuño  
[LinkedIn](https://www.linkedin.com/in/alejandro-ortuno-garcia-1bb778171/) | [GitHub](https://github.com/aleorgar)
