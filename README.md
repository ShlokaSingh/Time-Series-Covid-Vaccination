# 📈 Time Series Analysis of COVID-19 Vaccination Using Real-World Data  
*Forecasting with ARIMA on Our World in Data’s Global Vaccination Dataset*

This project explores worldwide COVID-19 vaccination progress and uses **ARIMA-based time series analysis** to forecast future vaccination rates. Built in early 2021 using R, it blends **exploratory data analysis**, **data visualization**, and **predictive modeling** to derive insights from real-world data.

> 🧠 Focus: Time Series Forecasting · Data Visualization · EDA  
> 📅 Completed: Q1 2021  
> 🔧 Tools: R, ARIMA, ggplot2, RMarkdown

---

## 🔍 Objective

- Analyze country-wise vaccination rollout data from early stages of the COVID-19 pandemic
- Visualize patterns, trends, and differences across nations
- Forecast daily vaccination growth using **ARIMA time series modeling**
- Summarize model performance using residuals, RMSE, and R² scores

---

## 🧠 Key Techniques Used

- 📊 **Exploratory Data Analysis (EDA)**  
  - Country comparisons  
  - Top performers in cumulative doses  
  - Time-based trend plots

- 🌍 **Geo Mapping & Visualizations**  
  - Choropleth maps of global vaccine progress  
  - Interactive plots via `plotly`

- 🔁 **Time Series Forecasting with ARIMA**  
  - Trained on India’s vaccination data  
  - Forecasted future values with 95% CI  
  - Residual checks and RMSE/R² evaluations

- 📉 **Regression Modeling**  
  - Simple linear regression to identify variable relationships

---

## 📦 Technologies & Packages

| Category        | Tools Used |
|----------------|------------|
| Data Wrangling | `dplyr`, `readr`, `tidyr` |
| Visualization  | `ggplot2`, `plotly`, `rworldmap`, `choroplethr` |
| Modeling       | `forecast`, `tseries`, `caret`, `caTools` |
| Reporting      | `RMarkdown` |

---

## 📊 Sample Forecast Performance

> *Model trained on India’s daily vaccination data:*

- **RMSE:** ~0.12  
- **R² Score:** ~0.89  
- Clear upward trend captured in ARIMA predictions with tight confidence intervals

---

## 👩‍💻 Author

**Shloka Singh**  
Data Scientist | Automation & Analytics Enthusiast  
🔗 [Connect on LinkedIn]([https://www.linkedin.com/in/shloka-singh/])

---

## 📝 License

This project was created for academic and demonstration purposes during Q1 2021.  
Data was sourced from the [Our World in Data](https://ourworldindata.org/covid-vaccinations) public dataset.

---

## ⭐ Repo Tags

`#TimeSeries` `#DataScience` `#ARIMA` `#R` `#COVID19`
