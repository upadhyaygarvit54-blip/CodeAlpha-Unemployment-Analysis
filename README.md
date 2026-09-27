# 📊 Unemployment Analysis with Python

## CodeAlpha Data Science Internship – Task 2

This project analyzes unemployment rate data from India using Python, Pandas, Matplotlib, and Seaborn. The objective is to clean and explore the dataset, visualize unemployment trends, investigate the impact of COVID-19, and identify regional, rural-urban, and monthly patterns.

## 🎯 Objectives

- Clean and preprocess unemployment data
- Perform exploratory data analysis (EDA)
- Analyze unemployment trends over time
- Compare unemployment rates across regions
- Compare Rural vs Urban unemployment
- Investigate the impact of COVID-19 on unemployment
- Identify monthly and possible seasonal patterns
- Generate insights relevant to economic and social policy discussions

## 📁 Dataset

The project uses the **Unemployment in India** dataset.

Important fields include:

- Region
- Date
- Frequency
- Estimated Unemployment Rate (%)
- Estimated Employed
- Estimated Labour Participation Rate (%)
- Area

The dataset covers approximately **May 2019 to June 2020**, allowing comparison between the pre-COVID period and the initial COVID-19 disruption.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Development environment |

## 🔍 Analysis Performed

### 1. Data Cleaning
- Removed unnecessary spaces from column names
- Converted dates to datetime format
- Converted numerical columns to appropriate numeric types
- Checked missing values
- Checked and removed duplicate records

### 2. Exploratory Data Analysis
Descriptive statistics were used to understand unemployment, employment, and labour participation.

### 3. Unemployment Trend Analysis
The project analyzes how unemployment changed over time using line charts.

### 4. Regional Analysis
Average unemployment rates were calculated for different regions to identify geographical differences.

### 5. Rural vs Urban Analysis
Unemployment rates were compared between Rural and Urban areas.

### 6. COVID-19 Impact
The data was divided into pre-COVID and COVID periods to examine changes in unemployment.

### 7. Monthly Analysis
Monthly averages were calculated to identify changes across months. Since the dataset covers only about one year, these results should be interpreted as monthly patterns rather than strong evidence of recurring seasonal trends.

### 8. Correlation Analysis
The relationship between unemployment rate and labour participation rate was examined using correlation analysis and a heatmap.

## 📈 Key Findings

- Overall average unemployment rate: **approximately 11.79%**
- Pre-COVID average: **approximately 9.51%**
- COVID-period average: **approximately 17.77%**
- Highest monthly average: **approximately 24.88% in May 2020**
- Rural average unemployment: **approximately 10.32%**
- Urban average unemployment: **approximately 13.17%**
- Highest individual observation: **approximately 76.74% for Puducherry Urban in April 2020**
- A clear increase in unemployment was observed during the COVID-19 period.

## 🦠 COVID-19 Impact

The analysis indicates a significant disruption in India's labour market during the COVID-19 period. Unemployment increased sharply around the beginning of the pandemic and lockdown period.

The results should be interpreted in the context of the dataset's limited time period, which ends in June 2020.

## 💡 Policy and Social Insights

The analysis highlights areas that can be considered when addressing unemployment:

- Strengthening employment-generation programs
- Supporting small businesses and MSMEs during economic disruptions
- Expanding skill-development and reskilling programs
- Providing targeted support to vulnerable workers
- Improving employment monitoring at regional levels
- Developing emergency employment and income-support mechanisms during major economic shocks

These are data-informed considerations rather than claims that any single policy will necessarily produce a particular outcome.

## 📊 Visualizations

The notebook includes:

- Unemployment rate trend
- Regional unemployment comparison
- Rural vs Urban comparison
- COVID-19 impact visualization
- Monthly unemployment trends
- Correlation heatmap

## 📂 Project Structure

```text
CodeAlpha-Unemployment-Analysis/
│
├── CodeAlpha_Task_2_Unemployment_Analysis.ipynb
├── Unemployment in India.csv
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/CodeAlpha-Unemployment-Analysis.git
```

### 2. Navigate to the project

```bash
cd CodeAlpha-Unemployment-Analysis
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

```text
CodeAlpha_Task_2_Unemployment_Analysis.ipynb
```

Run all cells to reproduce the analysis.

## 👨‍💻 Author

**Garvit Upadhyay**

B.Tech Computer Science Engineering  
Data Science & Machine Learning Enthusiast

## 🏢 Internship

**CodeAlpha – Data Science Internship**

**Task 2: Unemployment Analysis with Python**

## 📌 Conclusion

This project demonstrates how Python-based data analysis can be used to understand unemployment trends, regional differences, rural-urban disparities, and labour-market disruption associated with COVID-19.

It provides a practical example of combining data cleaning, exploratory data analysis, visualization, and statistical interpretation to extract insights from real-world economic data.
