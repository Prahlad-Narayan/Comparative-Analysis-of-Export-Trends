# Export Growth Showdown: China, India, USA (2010–2022) 🌍📈

This Jupyter Notebook, analyzes export growth for China, India, and the United States using World Bank data from 2010 to 2022. The project employs statistical and machine learning techniques to evaluate export trends, forecast future performance, and assess trade diversity, providing insights into global trade dynamics.

---

## Project Overview

This project examines export values (in trillion US$) and exports as a percentage of GDP for three major economies, focusing on:

- **Linear Regression**: Models historical export trends and forecasts exports to 2035, estimating when China’s export lead over the USA doubles.

- **Compound Annual Growth Rate (CAGR)**: Quantifies relative export growth rates across countries.

- **Method of Moments (MOM)**: Estimates the scale and volatility of export values.

- **Poisson Modeling**: Analyzes synthetic trade category counts to evaluate export diversity.

---

## Data Sources

- **WB_Data.csv**: Contains export values (in US$) and exports as a percentage of GDP for 2010–2022.

---

## Key Findings

### China  
China leads in export performance, with the **fastest annual growth rate** of **0.130 trillion US$/year** and the **highest export scale** (mean **μ = 2.534 trillion US$**). However, this growth is accompanied by **significant volatility** (standard deviation **σ = 0.546**), indicating sensitivity to global market fluctuations.

### United States  
The U.S. maintains **moderate export growth** at **0.054 trillion US$/year** but stands out for its **high export diversity** (Poisson **λ = 88.538**). This broad and balanced trade portfolio enhances the country's **economic resilience** in the face of global uncertainty.

### India  
India shows **strong relative growth** with a **6.7% compound annual growth rate (CAGR)**. While its export scale is smaller, its **moderate diversity** (**λ = 60.000**) highlights **significant potential for diversification** and future expansion.
