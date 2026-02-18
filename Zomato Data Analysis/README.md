
---

# 🍽️ Zomato Data Analysis Using 

## 📌 Project Overview

This mini data analytics project focuses on analyzing **Zomato restaurant data** to understand customer preferences, restaurant trends, and factors influencing ratings and online orders.
Using Python and popular data analysis libraries, the project performs **data cleaning, exploration, and visualization** to extract meaningful insights from the dataset.

---

## 📊 Dataset Description

The dataset used in this project contains restaurant-related information such as:

* Restaurant type
* Online ordering availability
* Table booking availability
* Ratings
* Cost for two people
* Votes received by restaurants

The dataset is loaded from a CSV file named:

```
Zomato-data-.csv
```

---

## 🛠️ Tools & Libraries Used

The following Python libraries are used throughout the analysis:

* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization

---

## 🔍 Project Workflow

### 1️⃣ Importing Required Libraries

All essential libraries are imported to support data analysis and visualization.

---

### 2️⃣ Creating the DataFrame

The Zomato dataset is read using Pandas and loaded into a DataFrame for further processing.

---

### 3️⃣ Data Cleaning & Preparation

To ensure accurate analysis, several preprocessing steps are performed:

* Conversion of the **rate** column into numerical (float) values by removing denominator characters
* Handling missing and inconsistent values
* Cleaning categorical and numerical features

---

### 4️⃣ Exploratory Data Analysis (EDA)

The notebook explores key questions such as:

* Distribution of restaurant ratings
* Relationship between **online ordering** and ratings
* Impact of **table booking** on customer preferences
* Cost distribution for two people
* Voting trends across restaurants

---

### 5️⃣ Data Visualization

Multiple visualizations are created to make insights more interpretable:

* Count plots
* Histograms
* Box plots
* Bar charts

These plots help in understanding trends, patterns, and relationships within the data.

---

## 📈 Key Insights

Some important observations from the analysis include:

* Restaurants offering **online ordering** tend to receive higher engagement
* Ratings vary significantly across restaurant categories
* Cost for two people plays a noticeable role in customer preferences
* Votes and ratings often show a positive correlation

*(All insights are derived directly from visual and statistical analysis in the notebook.)*

---

## ▶️ How to Run the Project

1. Clone this repository
2. Make sure the dataset file `Zomato-data-.csv` is in the same directory as the notebook
3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open and run the notebook:

   ```bash
   jupyter notebook Zomato_Data_Analysis.ipynb
   ```

---

## 📌 Conclusion

This project demonstrates a complete **data analytics workflow**—from raw data to insights—using Python.
It is a beginner-friendly yet practical example of **real-world exploratory data analysis**, making it ideal for learning and portfolio purposes.

---
