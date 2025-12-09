# ⛈️ temporal-weather-anomaly-detection

## Stranger Weather Ahead: Detecting Anomalies in Temporal Weather Data

This project investigates and implements various **unsupervised machine learning** and **statistical techniques** to identify unusual and anomalous patterns within time-series weather data. The goal is to provide insights valuable for nowcasting, climate monitoring, and disaster prediction.

---

## 🎯 Methods & Techniques

We explore a comparative approach using four distinct anomaly detection methods:

* **k-Nearest Neighbors (k-NN):** Used to identify data points isolated from their neighbors in feature space.
* **Z-Score Analysis:** A statistical method to flag values that deviate significantly (by standard deviations) from the mean.
* **Cluster Based Local Outlier Factor (CBLOF):** Detects outliers based on their proximity to nearby data clusters.
* **Autoencoders:** A neural network approach where reconstruction loss is used to identify anomalies (poorly reconstructed data points). 

---

## 💾 Dataset

The project utilizes the **Jenna Climate 2009-2016 dataset**, produced by the Max Planck Institute for Biogeochemistry. This temporal dataset provides high-granularity measurements (collected every 10 minutes) across 15 different weather features, including temperature, pressure, and humidity.

---

## 🚀 How to Run the Code

The complete analysis, code, and visualizations are available in a Google Colaboratory notebook.

[Click here to view the Google Colab Notebook](https://colab.research.google.com/drive/11pgCr76u33Ts37mT8WDtnEY7hn85bZNz?usp=sharing)
### Local Setup (For Environment Replication)

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/temporal-weather-anomaly-detection.git](https://github.com/YourUsername/temporal-weather-anomaly-detection.git)
    cd temporal-weather-anomaly-detection
    ```
2.  **Install the necessary dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```

---
## 📚 Full Report

For a detailed discussion of the methodology, results, and future work, please read the full article published by the Warwick Data Science Society:

**[Stranger Weather Ahead: Detecting Anomalies in Temporal Weather Data](https://medium.com/@WDSS/stranger-weather-ahead-detecting-anomalies-in-temporal-weather-data-9630eae33ecf)**

---
## 🤝 Project Team

* **Mariam Zenaishvili**
* **Evyanne Ewusie**
* **Vivek Chander**
* **Dogukan Turkoz**


---
