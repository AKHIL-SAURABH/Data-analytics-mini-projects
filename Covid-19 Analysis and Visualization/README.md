
---

# 🦠 COVID-19 Data Analysis & Visualization using Python & 

## 📌 Project Overview

The **COVID-19 pandemic** affected countries worldwide, creating an urgent need for data analysis and visualization to understand its spread and impact.

This project performs **exploratory data analysis (EDA)** and **interactive visualization** on global COVID-19 datasets using **Python, Pandas, and Plotly Express**.

The notebook analyzes:

* Global **confirmed cases**
* **Deaths and recovery statistics**
* **Country-wise comparisons**
* **Testing statistics**
* **WHO region distribution**
* **Temporal trends of cases**

The goal of the project is to transform raw pandemic data into **insightful visualizations** that help understand patterns, severity, and geographic distribution of COVID-19.

---

# 📊 Objectives of the Project

The main objectives of this analysis are:

* Understand the **global spread of COVID-19**
* Identify **countries with highest cases and deaths**
* Analyze **recovery patterns**
* Study **testing distribution across countries**
* Visualize **regional trends**
* Explore **time-based patterns of the pandemic**

---

# 🗂️ Dataset Description

Three datasets were used in this project.

## 1️⃣ `covid.csv`

This dataset contains **country-level statistics**.

| Column           | Description                   |
| ---------------- | ----------------------------- |
| Country/Region   | Name of the country           |
| Continent        | Continent of the country      |
| Population       | Population of the country     |
| TotalCases       | Total confirmed cases         |
| TotalDeaths      | Total deaths                  |
| TotalRecovered   | Total recovered cases         |
| ActiveCases      | Currently active cases        |
| Serious/Critical | Critical condition cases      |
| Tot Cases/1M pop | Cases per million population  |
| Deaths/1M pop    | Deaths per million population |
| TotalTests       | Total COVID tests conducted   |
| Tests/1M pop     | Tests per million population  |
| WHO Region       | WHO classification            |
| iso_alpha        | Country code                  |

---

## 2️⃣ `covid_grouped.csv`

This dataset contains **daily COVID statistics**.

| Column         | Description           |
| -------------- | --------------------- |
| Date           | Reporting date        |
| Country/Region | Country name          |
| Confirmed      | Confirmed cases       |
| Deaths         | Death cases           |
| Recovered      | Recovered cases       |
| Active         | Active cases          |
| New cases      | Daily new cases       |
| New deaths     | Daily deaths          |
| New recovered  | Daily recoveries      |
| WHO Region     | Region classification |

---

## 3️⃣ `coviddeath.csv`

This dataset contains **information about COVID-19 related deaths and contributing factors**.

It helps explore the **medical or demographic reasons behind fatalities**.

---

# ⚙️ Technologies Used

The project uses the following tools and libraries:

| Technology           | Purpose                    |
| -------------------- | -------------------------- |
| Python               | Programming language       |
| Pandas               | Data manipulation          |
| NumPy                | Numerical operations       |
| Matplotlib           | Static plotting            |
| Plotly Express       | Interactive visualizations |
| Plotly Graph Objects | Advanced charts            |
| WordCloud            | Text visualization         |
| Jupyter Notebook     | Development environment    |

---

# 📦 Project Workflow

The analysis follows these steps:

### 1️⃣ Importing Required Libraries

Libraries such as **Pandas, Plotly, and Matplotlib** are imported for data processing and visualization.

---

### 2️⃣ Loading the Datasets

Datasets are imported using:

```python
pd.read_csv()
```

Each dataset is explored using:

* `head()`
* `shape`
* `size`
* `info()`

to understand structure and missing values.

---

### 3️⃣ Data Exploration

Initial exploration includes:

* Checking dataset structure
* Understanding column types
* Detecting missing values
* Viewing summary statistics

This helps prepare the dataset for visualization.

---

# 📋 Dataset Preview

Below is a preview of the dataset used for analysis.

![Dataset Preview](https://github.com/AKHIL-SAURABH/Data-analytics-mini-projects/blob/main/Covid-19%20Analysis%20and%20Visualization/table.jpg)

The table shows country-level COVID-19 statistics including population, cases, deaths, recoveries, testing data, and WHO region classification.

---



# 📊 Visualizations Included in the Project

The notebook generates multiple visualizations to understand the pandemic patterns.

### Types of visualizations used:

* 📈 Line Charts
* 📊 Bar Charts
* 🔵 Bubble Charts
* 🌍 Choropleth Maps
* 📉 Scatter Plots
* ☁ WordCloud

These graphs allow deeper insight into:

* Country comparisons
* Region distribution
* Testing trends
* Time-based spread of COVID-19

---

# 📊 Key Analysis & Visualizations

## 🌍 Global Case Distribution

Shows which countries had the **highest confirmed cases**.

This helps identify **pandemic hotspots globally**.

---

## ☠ Death Rate Analysis

Analyzes the **death counts across countries**.

Important observations include:

* Countries with high fatalities
* Regions with severe outbreaks

---

## 💚 Recovery Trends

Tracks how recovery rates differ between countries.

This indicates **effectiveness of healthcare systems and response measures**.

---

## 🧪 Testing Analysis

Testing statistics help understand:

* Countries performing the most tests
* Testing efficiency relative to population

---

## 🌎 WHO Region Analysis

Countries are grouped based on **WHO regions** to study regional patterns.

---

## 📅 Time-Series COVID Spread

Using `covid_grouped.csv`, we visualize:

* Daily confirmed cases
* Daily deaths
* Daily recoveries

This helps track **how the pandemic evolved over time**.

---

# 📸 Visualization Outputs

Because **GitHub cannot render Plotly interactive graphs**, PNG versions of the visualizations were added inside the notebook so they can still be displayed on GitHub.

Examples include:

* Country case comparisons
* Global trend charts
* Regional distribution graphs
* Testing statistics charts

---

# ⚠ IMPORTANT NOTE

🚨 **Plotly graphs cannot render directly on GitHub.**

GitHub does not support interactive **Plotly JavaScript visualizations** inside Jupyter notebooks.

Because of this limitation:

* Interactive graphs appear **blank on GitHub**
* Only **static images (PNG/JPG)** are visible

To solve this issue:

✔ Screenshots of the Plotly graphs were **inserted into the notebook**
✔ These images allow the visualizations to be viewed on GitHub

However, **one Plotly visualization could not be embedded properly**, so it is included below.

---

# 📌 Missing Visualization (Rendered in README)

This visualization could not render correctly in the notebook on GitHub due to Plotly rendering limitations.

Therefore, it is shown here in the README.

📷 Insert the image here:

```
(Add the missing visualization image here)
```

Example:

```
![Plotly Visualization](images/plotly_visualization.png)
```

---

# 📈 Key Insights from the Analysis

Some major observations from the data:

* The **USA and Brazil** reported the highest number of confirmed cases.
* **India** had a large number of cases relative to its population.
* **European countries** showed high deaths per million population.
* Testing rates varied significantly between countries.
* Some regions showed faster recovery trends than others.

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/covid19-analysis.git
```

---

### 2️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib plotly wordcloud
```

---

### 3️⃣ Run the Notebook

Open the notebook using:

```
Jupyter Notebook
```

or

```
Jupyter Lab
```

Run all cells to reproduce the analysis.

---

# 📁 Project Structure

```
Covid19-Analysis
│
├── Covid-19_Analysis.ipynb
├── covid.csv
├── covid_grouped.csv
├── coviddeath.csv
├── images
│   ├── graphs.png
│   └── visualization.png
│
└── README.md
```

---

# 🎯 Conclusion

This project demonstrates how **data science and visualization techniques** can be used to understand complex global events such as the COVID-19 pandemic.

By combining **Python, Pandas, and Plotly**, we transformed raw datasets into meaningful insights about:

* Global case distribution
* Death and recovery patterns
* Testing statistics
* Regional pandemic trends

Such visual analytics help policymakers, researchers, and the public **better understand pandemic dynamics**.

---

