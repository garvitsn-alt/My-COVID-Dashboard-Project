\#🌍 COVID-19 Global Data Analysis Dashboard



This project demonstrates my ability to clean real-world datasets using Python and build insightful dashboards using Power BI.



\## 🚀 Tools Used

- \*\*Python (pandas, NumPy)\*\* for data cleaning

\- \*\*Power BI\*\* (DAX, Visualizations) for building interactive dashboards

\- \*\*Git/GitHub\*\* for version control and portfolio hosting



\## Data source: \[https://www.kaggle.com/datasets/jocelyndumlao/global-covid-19-statistics-jan-2025](#)



\## 🔧 Tools Used

\- \*\*Python (pandas)\*\* for data cleaning

\- \*\*Power BI\*\* for building interactive dashboards

\- \*\*Git/GitHub\*\* for version control and portfolio hosting





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



\## 🚀 How to Use

1\. Run the `CovidCleanedDataSet.py` script

2\. Open the `dashboardCovid.pbix` file in Power BI Desktop

3\. Load the cleaned CSV and explore the visuals



\## 📷 Screenshots

!\[Dashboard Screenshot 1](https://raw.githubusercontent.com/garvitsn-alt/My-COVID-Dashboard-Project/2f2acc50b31918759112b768000489dd1ae44c47/Dashboard-Screenshot-1.png)

!\[Dashboard Screenshot 2](https://raw.githubusercontent.com/garvitsn-alt/My-COVID-Dashboard-Project/2f2acc50b31918759112b768000489dd1ae44c47/Dashboard-Screenshot-2.png)

!\[Dashboard Screenshot 3](https://raw.githubusercontent.com/garvitsn-alt/My-COVID-Dashboard-Project/2f2acc50b31918759112b768000489dd1ae44c47/Dashboard-Screenshot-3.png)



\## 📁 Files

\- `CovidCleanedDataSet.ipynb`: Python cleaning script

\- `dashboardCovid.pbix`: Power BI file

\- `cleanedCovidData.csv`: Clean dataset

\- `Covid\_stats\_Jan2025.csv`: Raw dataset



\## 👤 Author

Garvit Saini — transitioning from QA Automation to Data Science





