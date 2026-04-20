# 🏅 Olympic Success: A Statistical Socio-Economic Study
**By: Yuanyuan Wei** | *Maths & Stats Graduate* | 📍 Montreal, QC (PR Holder)

## 📌 Project Overview
This project investigates the relationship between a nation's socio-economic factors (GDP and Population) and its performance in the Olympic Games. Using data from 1896 to 2016, I conducted a multivariate statistical analysis to determine the primary drivers of athletic success.

### 🔍 Key Research Questions
1. Is there a statistically significant correlation between a country's GDP and its medal count?
2. Does population size provide a significant advantage after controlling for wealth?
3. Which nations are most "efficient" at producing medals relative to their economic resources?

## 🛠️ Technical Toolkit
- **Language:** R
- **Libraries:** `dplyr` (data cleaning), `ggplot2` (visualization), `car` (VIF & Multicollinearity), `tidyr` (data reshaping).
- **Statistical Methods:** Multivariate Linear Regression, ANOVA, Hypothesis Testing (P-values), and Correlation Matrices.

## 📊 Major Findings
- **Economic Correlation:** Found a strong positive correlation (r = 0.77) between GDP and Total Medals.
- **Efficiency Index:** Developed a custom KPI to identify "over-performing" nations.
- **Log-Scale Modeling:** Used log-transformation to normalize highly skewed GDP data for more accurate regression results.

## 📄 Full Report
For the detailed 23-page statistical methodology and results, please see the [Full PDF Report](./olympic_report.pdf).

## 🚀 How to Run the Analysis
1. Clone the repo: `git clone https://github.com`
2. Open `analysis_script.R` in RStudio.
3. Ensure the datasets in the `/data` folder are loaded.
