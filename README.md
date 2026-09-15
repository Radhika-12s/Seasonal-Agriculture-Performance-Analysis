# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

**Seasonal Agriculture Performance Analysis** is a Major Data Analytics Project focused on understanding agricultural performance across different seasons, crops, geographical areas, farming practices, environmental conditions, resource usage, and economic outcomes.

The project analyzes the dataset using Python-based data analytics techniques to identify seasonal patterns, variations, relationships, unusual observations, and meaningful insights that can support better agricultural planning and decision-making.

---

## 🎯 Problem Statement

Agricultural performance can vary significantly across seasons due to differences in environmental conditions, farming practices, resource usage, crop selection, and economic factors.

This project aims to analyze the available agricultural data to understand:

* Seasonal differences in agricultural performance
* Patterns and trends across crops and regions
* Relationships between environmental and farming variables
* Resource usage and water efficiency
* Production and economic performance
* Disease and pest risk variations
* Unusual observations and outliers
* Areas requiring further investigation

---

## 🎯 Objectives

The main objectives of this project are to:

1. Explore and understand the agricultural dataset.
2. Identify and handle missing values and data-quality issues.
3. Analyze agricultural performance across different seasons.
4. Compare crops, irrigation methods, and farm-size categories.
5. Study relationships between environmental, farming, production, and economic variables.
6. Analyze resource usage and water efficiency.
7. Identify unusual observations using statistical outlier analysis.
8. Use suitable statistical and visualization techniques to interpret the data.
9. Develop meaningful evidence-based insights.
10. Provide recommendations based on the analysis.

---

## 📊 Dataset

The dataset contains **4,000 farm records and 28 original variables** covering agricultural conditions and performance.

### Major Categories

* **Geographical:** State, District
* **Crop & Season:** Crop, Season
* **Farm Characteristics:** Farm Area
* **Environmental:** Rainfall, Temperature, Humidity, Sunlight, Soil pH, Soil Moisture
* **Nutrients:** Nitrogen, Phosphorus, Potassium
* **Farming Practices:** Irrigation Method, Fertilizer, Pesticide, Seed Quality
* **Production:** Yield, Production
* **Economic:** Market Price, Total Cost, Revenue, Profit
* **Resource Usage:** Water Used, Water Efficiency
* **Risk:** Disease/Pest Risk

The dataset contains agricultural records from multiple states, districts, crops, seasons, and irrigation methods.

---

## 🧹 Data Quality & Preprocessing

The dataset was examined for:

* Missing values
* Duplicate records
* Duplicate Farm IDs
* Data types
* Unique categorical values
* Unusual observations
* Distribution and variability

Missing values were treated using **contextual median imputation**:

* Rainfall → median by Season
* Soil Moisture → median by Season
* Yield → median by Crop and Season

No records were removed solely because of the identified missing values.

---

## 🔎 Analysis Performed

The project includes the following analyses:

### 1. Statistical Analysis

* Descriptive statistics
* Season-wise statistical comparison
* Mean and median comparison
* Variability analysis

### 2. Univariate Analysis

Distribution analysis of:

* Yield
* Production
* Profit
* Water Usage
* Water Efficiency
* Disease/Pest Risk

### 3. Outlier Analysis

The **Interquartile Range (IQR)** method was used to identify potential outliers in important numerical variables.

Variables examined include:

* Yield
* Production
* Profit
* Water Used
* Water Efficiency

### 4. Bivariate Analysis

Relationships were examined between variables such as:

* Rainfall and Yield
* Soil Moisture and Yield
* Farm Area and Production
* Fertilizer and Yield
* Seed Quality and Yield
* Production and Profit
* Water Usage and Profit
* Market Price and Profit
* Total Cost and Profit
* Revenue and Profit

Categorical comparisons were also performed for:

* Irrigation Method vs Yield
* Crop vs Yield
* Season vs Yield

### 5. Multivariate & Seasonal Analysis

The project compares agricultural performance across multiple dimensions, including:

* Crop and Season
* Season and agricultural performance
* Irrigation and production
* Irrigation and disease/pest risk

### 6. Additional Analysis

Additional student-driven analyses include:

* Average Yield by Irrigation Method
* Farm Size Category vs Average Profit
* Farm Size Category vs Average Yield
* Crop Production by Irrigation Method
* Disease/Pest Risk by Irrigation Method

---

## 📈 Key Findings

Based on the analysis performed in the notebook:

* **Kharif** recorded the highest average yield and production among the three seasons.
* Kharif also recorded the highest average profit.
* **Zaid** recorded the lowest average yield, production, profit, and water efficiency.
* Zaid showed the highest average water usage among the three seasons.
* Kharif had the highest average disease/pest risk.
* Yield and production showed strong right-skewed distributions, indicating substantial variation in the dataset.
* Profit had the highest proportion of IQR-detected outliers among the major numerical variables examined.
* Crop performance varied across different seasons.
* Irrigation methods showed differences in yield, production, resource efficiency, and disease/pest risk.
* The analysis highlights the importance of considering both agricultural performance and resource usage when comparing seasons and farming practices.

> **Note:** These findings describe patterns observed in the dataset. They do not establish causal relationships.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Google Colab**

---

## 📂 Project Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── README.md
├── Seasonal_Agriculture_Performance_Analysis.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── Major Project_Seasonal Agriculture Performance Analysis.pdf
└── VOIS_Major_Project_PPT_Submission.pptx
```

---

## ▶️ How to Run the Project

1. Open the `.ipynb` notebook in **Google Colab**.
2. Upload the `seasonal_agriculture_performance_dataset.csv` file to the Colab environment.
3. Run the notebook cells sequentially.
4. Review the generated statistical outputs, tables, and visualizations.
5. Use the analysis and findings presented in the notebook for reference.

---

## 🔮 Future Scope

The analysis can be extended in the future by:

* Adding larger and more diverse agricultural datasets.
* Incorporating additional real-world environmental and geographical data.
* Performing time-series analysis using multi-year agricultural records.
* Studying additional crop-specific and regional patterns.
* Developing interactive dashboards for easier exploration.
* Applying predictive analytics or machine-learning techniques as a future extension of the project.
* Integrating real-time agricultural and weather information.

---

## 👩‍💻 Author

**Radhika Ashok Bhadoriya**

BCA — Prestige Institute of Management & Research, Gwalior

Academic Session: **2024–2027**

---

## 📚 Project Context

This project was completed as part of the **VOIS AICTE Major Project** in the Data Analytics / Data Visualization learning program.

---

## ⭐ Acknowledgement

Thanks to **VOIS, AICTE, and the project mentors** for providing the project resources, dataset, and learning opportunity.
