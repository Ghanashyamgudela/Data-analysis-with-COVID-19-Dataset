# 📊 COVID-19 Data Analysis

## 📌 Overview  
This project performs an exploratory data analysis (EDA) on COVID-19 case data across different countries.  
The goal is to understand patterns in confirmed cases, recoveries, active cases, and deaths, as well as generate meaningful visual insights.  

---

## 📂 Dataset  
- **Source**: (e.g., Johns Hopkins University, WHO, Kaggle — update this)  
- **Format**: CSV  
- **Index**: `Country/Region`  
- **Columns**:
  - `Confirmed` → Total confirmed cases  
  - `Deaths` → Total deaths  
  - `Recovered` → Total recovered cases  
  - `Active` → Current active cases  
  - `New cases`, `New deaths`, `New recovered`  
  - `Deaths / 100 Cases` → Fatality rate (%)  
  - `Recovered / 100 Cases` → Recovery rate (%)  

---

## ⚙️ Technologies Used  
- [Python](https://www.python.org/)  
- [Jupyter Notebook](https://jupyter.org/)  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)  

---

## 📈 Analysis Performed  
1. **Data Cleaning & Preprocessing**  
   - Converted columns to numeric (`pd.to_numeric`)  
   - Set `Country/Region` as index  
   - Checked & handled missing values  

2. **Exploratory Data Analysis (EDA)**  
   - Top countries by confirmed cases  
   - Highest recovery rates  
   - Deaths per 100 cases  
   - Distribution of active cases  

3. **Visualizations**  
   - Bar charts: confirmed, deaths, recovered  
   - Comparative plots for multiple countries  
   - (If using time series) Line plots for trends  

---

## 📊 Key Insights  
- Countries like **China, USA, Italy** had highest early confirmed cases.  
- Recovery rates varied widely (25% – 90%).  
- Fatality rates (`Deaths / 100 Cases`) indicated critical regional differences.  
- Visualizations made country-level comparison much clearer.  

---

## 🚀 How to Run  
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/covid19-analysis.git
   cd covid19-analysis
