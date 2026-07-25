# Covid-19-EDA

This project presents an **Exploratory Data Analysis (EDA)** of a COVID-19 weekly dataset using **Python**. The objective is to analyze trends in COVID-19 deaths, non-COVID deaths, expected deaths, excess deaths, and population across different countries and time periods.

The analysis follows a complete data analysis workflow, including data cleaning, preprocessing, validation, statistical analysis, and visualization to uncover meaningful insights from the dataset.

---

##  Objectives

* Clean and preprocess the COVID-19 dataset
* Explore trends in mortality over time
* Compare expected deaths with actual deaths
* Analyze excess deaths across countries
* Visualize important relationships between variables
* Extract meaningful insights using EDA techniques

---

##  Dataset Information

**Dataset Name:** COVID Weekly Dataset

### Dataset Features

* Country
* Region
* Start Date
* End Date
* Population
* COVID Deaths
* Non-COVID Deaths
* Total Deaths
* Expected Deaths
* Excess Deaths
* Excess Death Percentage
* Excess Deaths per 100,000 Population

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

##  Exploratory Data Analysis

The project includes:

* Data loading and inspection
* Missing value analysis
* Duplicate value detection
* Datetime conversion
* Data type optimization
* Correlation analysis (Spearman)
* Validation of death-related calculations
* Summary statistics
* Data visualization

---

##  Visualizations Included

*  Total Deaths vs Expected Deaths (Line Plot)
*  COVID vs Non-COVID Deaths Trend
*  Top 5 Countries by Excess Deaths
*  Top Countries by Excess Deaths per 100K Population
*  Correlation Heatmap
*  Boxplot of Excess Death Percentage
*  Heatmap of Top 10 Countries
*  Year-wise Death Comparison
*  Pairplot of Numerical Features
*  Scatter Plot: Population vs Excess Deaths

---

##  Project Screenshots



### Dashboard / Charts

```
README.md
images/
│── line_plot.png
│── heatmap.png
│── bar_chart.png
│── pairplot.png
│── scatter_plot.png
```

Example:

```markdown
## Line Plot

![Line Plot](images/line_plot.png)

## Heatmap

![Heatmap](images/heatmap.png)

## Pairplot

![Pairplot](images/pairplot.png)
```

---

## 📋 Project Structure

```
COVID-EDA/

│── Covid-EDA(Notebook).ipynb
│── covid_weekly_dataset.csv
│── README.md
│── images/
│     ├── line_plot.png
│     ├── heatmap.png
│     ├── scatter_plot.png
│     ├── pairplot.png
│     └── bar_chart.png
```

---

## Installation

Clone this repository

```bash
git clone https://github.com/yourusername/COVID-EDA.git
```

Move into the project directory

```bash
cd COVID-EDA
```

Install required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Covid-EDA(Notebook).ipynb
```

---

##  Key Findings

* Total deaths generally exceeded expected deaths during peak COVID periods.
* Excess deaths varied significantly across different countries.
* COVID deaths showed noticeable temporal trends throughout the dataset.
* Strong relationships exist between several mortality-related variables.
* Data validation confirmed consistency between key death metrics.

---

##  Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Validation
* Data Visualization
* Statistical Analysis
* Python Programming
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

##  Future Improvements

* Build an interactive dashboard using Power BI or Tableau.
* Develop predictive models for mortality forecasting.
* Perform country-level comparative analysis.
* Create an interactive web application using Streamlit.

---

##  Author

**Disha Singh**


---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
