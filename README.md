# Time Series Analysis of Electricity Demand (Victoria, May 2014)

This project analyzes half-hourly electricity demand data for Victoria, Australia (May 2014), using the `vic_elec` dataset from the **fpp3** R package.  
The analysis applies moving averages with different window sizes to explore how smoothing affects the interpretation of demand patterns.

## 📊 Objectives
- Extract one month of half-hourly demand data (May 2014).
- Apply moving averages with 12-hour, 24-hour, and 1-week windows.
- Compare raw demand vs. smoothed demand.
- Interpret the trade-offs between short- and long-window smoothing.

## 🛠️ Tools Used
- **R**: Data wrangling, analysis, and visualization  
- **Libraries**: fpp3, slider, ggplot2, lubridate  
- **R Markdown**: Reproducible reporting

## 🔑 Key Findings
- **Raw demand** shows large spikes and strong daily cycles.  
- **12-hour & 24-hour moving averages** smooth the data while preserving daily trends.  
- **1-week moving average** removes daily fluctuations and highlights the broader monthly trend:
  - Demand decreased in the first half of May.
  - Demand increased in the second half.  

## 📂 Repository Contents
- `analysis.Rmd` → R Markdown file with code and explanations  
- `analysis.html` → Rendered report with plots and commentary  

## 🚀 Skills Demonstrated
- Time series analysis  
- Moving average smoothing techniques  
- Data visualization with ggplot2  
- Reproducible research using R Markdown  

---
