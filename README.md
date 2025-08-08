\#🌍 COVID-19 Global Data Analysis Dashboard



This project demonstrates my ability to clean real-world datasets using Python and build insightful dashboards using Power BI.



\## 🚀 Tools Used

\- Python (Pandas, NumPy)

\- Power BI (DAX, Visualizations)

\- Data source: \[https://www.kaggle.com/datasets/jocelyndumlao/global-covid-19-statistics-jan-2025](#)



\## 🧹 Data Cleaning (Python)

\- Drop Irrelevant columns

\- Filled total recovered value for missing countries according to mean recover ratio (calculated from all other values and then finding mean) w.r.t population of the country

\- Calculated and filled active cases = Total Cases - Deaths - Recovered

\- Filled total tests calculated from mean ratio of other countries

\- Filled missing population, calculate through mean of infection ratio on Total cases

\- Removed missing/null values and filled null values to 0

\- Converted comma-separated numbers to numeric





\## 📊 Power BI Dashboard Features

\- Total Cases, Deaths, Tests done, Recovered by Country/Continent

\- KPI cards for Total Cases, Total Deaths, Country Name

\- Pie Chart

\- Bar chart for top ten countries with most cases

\- Map demonstrating affected countries with its total cases, total deaths, and population in tool tip.

\- Interactive Filters



\## 📷 Screenshots

!\[Dashboard Screenshot 1](images/dashboard\_screenshot1.png)

!\[Dashboard Screenshot 2](images/dashboard\_screenshot1.png)

!\[Dashboard Screenshot 3](images/dashboard\_screenshot1.png)



\## 📁 Files

\- `scripts/clean\_data.py`: Python cleaning script

\- `dashboard/covid\_dashboard.pbix`: Power BI file

\- `data/covid\_data.csv`: Raw dataset

