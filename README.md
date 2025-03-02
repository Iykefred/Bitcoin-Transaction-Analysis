# Bitcoin-Transaction-Analysis
Exploratory Data Analysis (EDA) of Bitcoin blockchain data, including transaction trends, correlation analysis, and anomaly detection.
Here’s a well-structured **README-style note** you can add to your **GitHub repository** to explain your Bitcoin blockchain data analysis:

---

# **Bitcoin Blockchain Data Analysis**

## **Overview**
This project performs **exploratory data analysis (EDA)** on Bitcoin blockchain data. The dataset consists of **13,298 blocks**, covering key blockchain parameters such as transaction counts, block rewards, fees, and mining difficulty.

## **Objectives**
The goal of this analysis is to:
1. **Understand blockchain transaction trends** over time.
2. **Analyze correlation** between key blockchain attributes.
3. **Detect anomalies** in transaction counts and fees.

## **Analysis Performed**
### **1. Correlation Analysis**
- A correlation matrix was generated to identify relationships between numerical features.
- **Key Findings:**
  - Higher transaction counts are associated with increased fees and block sizes.
  - Mining difficulty increases as the blockchain height progresses.
  - Negative correlation exists between `Bits` and `Block_No`, reflecting mining adjustments.

### **2. Visualization of Key Trends**
- **Transaction Count Over Time:** Shows fluctuations in blockchain activity.
- **Transaction Fees Over Time:** Highlights periods of increased transaction costs due to congestion.

### **3. Anomaly Detection**
- Used **Z-score analysis** to identify blocks with **extremely high transaction counts**.
- Outliers detected indicate **spikes in blockchain activity**, potentially due to increased demand or unusual miner behavior.

## **Implementation**
- The analysis was conducted using **Python (Pandas, NumPy, Matplotlib)**.
- The dataset was preprocessed, cleaned, and sorted for time-series analysis.
- Visualizations were generated to highlight blockchain transaction trends.

## **How to Use This Repository**
### **Prerequisites**
- Python 3.x
- Required libraries:
  ```bash
  pip install pandas numpy matplotlib
  ```

### **Run the Analysis**
1. Clone the repository:
   ```bash
   git clone https://github.com/iykefred/bitcoin-blockchain-analysis.git
   cd bitcoin-blockchain-analysis
   ```
2. Run the script:
   ```bash
   python analysis_script.py
   ```
3. Review the correlation matrix, trend visualizations, and anomaly detection results.

## **Next Steps**
- Extend the analysis to include **transaction volume and miner rewards**.
- Apply **machine learning models** to predict blockchain congestion patterns.
- Incorporate **real-time blockchain data** for continuous monitoring.

## **Contributors**
- **Iykefred**
- Open to collaboration! Feel free to submit a pull request.

---

Would you like any modifications or additions? 🚀
