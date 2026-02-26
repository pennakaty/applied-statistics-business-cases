# Professional Case Study: Applied Statistical Methods in Python 📊

This repository contains a comprehensive application of descriptive and inferential statistics to solve real-world business problems. Using Python's scientific ecosystem, I have modeled scenarios ranging from manufacturing quality control to telemarketing performance and banking service efficiency.

## 📌 Project Overview
The objective of this project is to demonstrate how statistical distributions can be used to drive data-driven decisions. Each analysis compares manual mathematical formulas with automated results from the `scipy.stats` library to ensure 100% accuracy.

## 📋 Analytical Modules

### 1. Educational Performance (Descriptive Statistics)
* **Objective:** Analyze central tendency (Mean, Median, Mode) and data symmetry.
* **Key Concept:** Understanding how outliers affect distribution shape (Skewness).

### 2. Manufacturing & Sales (Binomial Distribution)
* **Quality Control:** Modeling defect rates (5%) in production batches to predict failure probability.
* **Conversion Analysis:** Evaluating telemarketing efficiency and the likelihood of hitting hourly sales targets.

### 3. Operational Flow (Poisson Distribution)
* **Traffic Modeling:** Forecasting call center arrival rates to optimize staffing.
* **Scalability:** Adjusting the rate ($\lambda$) for different time windows (from 5-minute peaks to 8-hour shifts).

### 4. Service Efficiency (Exponential Distribution)
* **Customer Experience:** Modeling bank teller service times to identify bottlenecks.
* **Service Levels:** Calculating the probability of meeting specific service time windows (e.g., service under 3 minutes).

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `SciPy (stats)`: For probability mass/density functions (PMF/PDF) and CDF.
    * `Pandas`: For data manipulation.
    * `NumPy`: For numerical operations and scaling.
    * `Matplotlib`: For visualizing distribution curves and skewness.

## 🚀 How to Use
1. Clone the repository.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy scipy matplotlib
