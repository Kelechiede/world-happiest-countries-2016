# 🌍 World Happiest Countries Report 2016 – Data Analysis & Visualization

This project is part of the **IBM Data Analyst Professional Certificate** program on Coursera. It explores how economic, health, and social factors contribute to national happiness using the **World Happiness Report 2016** dataset.

This project is part of the [IBM Data Analyst Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-analyst). It involves data preparation, exploration, and visualization based on the World Happiness Report.


---

## 📌 Project Objectives

- Clean and prepare the dataset
- Analyze core factors (GDP, family, health, freedom, etc.)
- Visualize patterns using multiple chart types
- Combine insights into one cohesive dashboard notebook

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn, Plotly
- Jupyter Notebook
- GitHub for publishing

---

# About the Dataset
This project uses data from the <a href="https://www.kaggle.com/datasets/unsdsn/world-happiness/data" target="_blank"><strong> World Happiness Report</strong></a>, a widely cited global survey that ranks countries based on their citizens' perceived well-being. The report draws on recent research in the science of happiness to explain variations in life satisfaction across nations. The dataset is publicly available on <a href="https://www.kaggle.com" target="_blank"><strong>Kaggle</strong></a> and is released under the <a href="https://creativecommons.org/publicdomain/zero/1.0/" target="_blank"><strong>CC0: Public Domain license</strong></a>, making it freely usable for analysis and visualization.

# Dataset Attributes

| **Variable**                      | **Description**                                                                                                                                               |
|----------------------------------|-------------------------------------------------------------------------------------------------------------------|
| `Country`                        | Name of the country                                                                                               |
| `Region`                         | Region the country belongs to                                                                                     |
| `Happiness Rank`                 | Rank of the country based on the Happiness Score                                                                  |
| `Happiness Score`                | A metric measured in 2016 by asking people: "How would you rate your happiness?"                                  |
| `Lower Confidence Interval`      | Lower bound of the confidence interval for the Happiness Score                                                    |
| `Upper Confidence Interval`      | Upper bound of the confidence interval for the Happiness Score                                                    |
| `Economy (GDP per Capita)`       | The extent to which GDP contributes to the calculation of the Happiness Score                                     |
| `Family`                         | The extent to which family contributes to the calculation of the Happiness Score                                  |
| `Health (Life Expectancy)`       | The extent to which life expectancy contributes to the calculation of the Happiness Score                         |
| `Freedom`                        | The extent to which freedom contributes to the calculation of the Happiness Score                                 |
| `Trust (Government Corruption)`  | The extent to which trust in government contributes to the calculation of the Happiness Score                     |
| `Generosity`                     | The extent to which generosity contributes to the calculation of the Happiness Score                              |
| `Dystopia Residual`              | Represents unexplained components of the score. Reflects how the six factors under/over the average value is approximately zero globally.       |


---
## 📈 What’s Inside the Notebook

The notebook includes:

- ✅ Data Cleaning & Preprocessing
- ✅ Exploratory Data Analysis (EDA)
- ✅ Visualizations:
  - Bar Chart: Top 10 Happiest Countries
  - Correlation Matrix (Heatmap)
  - GDP vs Happiness Score (Scatter Plot)
  - Happiness Score by Region (Pie Chart)
  - Interactive Map (GDP + Life Expectancy Tooltip)

---

## 🖥️ Interactive Dashboard Notebook

All charts, insights, and narrative have been combined into a single notebook.

- 🔗 [View Dashboard Notebook (HTML)](dashboard/World_HappiestFolks_Report2016.html)
- 📄 [Download as PDF](dashboard/World_HappiestFolks_Report2016.pdf)

> 💡 This notebook includes an **interactive map** powered by Plotly — best viewed in a Jupyter environment.

---

## 🧠 Key Takeaways

- **GDP**, **Life Expectancy**, and **Family Support** are the most influential predictors of happiness.
- Regions like **Western Europe** lead globally, while regions like **Sub-Saharan Africa** have lower scores.
- Economic and social indicators align well with happiness levels, as seen in both correlation and geographic visualizations.

---

## 📜 Certification

[![IBM Certificate Thumbnail](certification/ibm-data-visualization-thumbnail.png)](https://www.coursera.org/account/accomplishments/verify/9DJH9MB4L5XQ)

[Please verify here](https://www.credly.com/earner/earned/badge/350e2c8d-5996-4406-b1a13af5ae0e)
---

## 📁 Project Structure

```plaintext
world-happiness-2016/
├── data/
├── notebooks/
│   └── World_HappiestFolks_Report2016.ipynb
├── dashboard/
│   ├── World_HappiestFolks_Report2016.html
│   └── World_HappiestFolks_Report2016.pdf
├── certification/
│   └── ibm-data-visualization-thumbnail.png
├── visuals/
└── README.md
