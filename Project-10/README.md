
# 🦠 COVID-19 Data Analysis and Visualization

<p align="center">
  <b>Exploring COVID-19 data using Python, Pandas, NumPy, Matplotlib, and Seaborn</b>
</p>

---

## 📌 About the Project

This project focuses on analyzing and visualizing COVID-19 data using Python. The dataset is downloaded from Kaggle and contains information about confirmed cases, deaths, recoveries, countries, and observation dates.

The main goal of this project is to clean the dataset, perform basic data analysis, and create visualizations to better understand COVID-19 statistics.

## 🎯 Project Objectives

- Analyze COVID-19 data using Python.
- Identify and handle missing values.
- Calculate active cases and death percentages.
- Classify records based on confirmed cases and death levels.
- Compare COVID-19 statistics across countries.
- Visualize data using line charts, bar charts, and heatmaps.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numerical calculations and conditions |
| Matplotlib | Creating charts and graphs |
| Seaborn | Creating statistical visualizations |
| Jupyter Notebook | Writing and running Python code |

## 📂 Project Structure

```text
Project-10/
│
├── Final_Project.ipynb
├── covid_19_data.csv
└── README.md
```

## 📊 Dataset Information

**Dataset:** COVID-19 Data

**Source:** Kaggle

The dataset includes columns such as:

- `ObservationDate` — Date of the recorded observation.
- `Province/State` — Province or state, when available.
- `Country/Region` — Country or region name.
- `Confirmed` — Reported confirmed cases.
- `Deaths` — Reported deaths.
- `Recovered` — Reported recoveries.

## ⚙️ Features

### 1. Data Cleaning
- Checks missing values in the dataset.
- Replaces missing values in the `Confirmed`, `Deaths`, and `Recovered` columns with zero.
- Converts the observation date into a proper date format.

### 2. Data Analysis
- Calculates active cases.
- Calculates the percentage of reported confirmed cases represented by reported deaths.
- Classifies records as `Cases Found` or `No Cases`.
- Categorizes death counts into different levels.
- Groups records by country for comparison.

### 3. Data Visualization

📈 **Line Chart**
- Displays reported confirmed cases over time.

📊 **Bar Chart**
- Compares confirmed-case records across the top 10 countries.

🔥 **Heatmap**
- Visualizes confirmed cases, deaths, and recoveries for the selected countries.

## 📦 Installation

Make sure Python is installed on your computer.

Install the required libraries using the following command:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

## ▶️ How to Run the Project

1. Download or clone this project to your computer.
2. Keep `Final_Project.ipynb` and `covid_19_data.csv` in the same folder.
3. Open the project folder in VS Code or Jupyter Notebook.
4. Open `Final_Project.ipynb`.
5. Run the notebook cells in order, starting from the first cell.
6. View the analysis results and visualizations.

## 📈 Expected Results

After running the notebook, you will see:

- A summary of missing values.
- Additional columns for active cases, death percentage, result, and death level.
- A country-wise summary of COVID-19 statistics.
- A line chart showing confirmed cases over time.
- A bar chart comparing countries.
- A heatmap comparing COVID-19 statistics.

The charts help explore patterns in the dataset and compare the recorded statistics.

## ⚠️ Data Limitations

The dataset may contain cumulative daily records. Adding confirmed cases across multiple dates can count the same cases more than once.

Therefore, country totals and trend charts should be interpreted carefully. The current analysis is intended for learning data analysis and visualization, rather than producing official epidemiological estimates.

The death-level categories are simple, user-defined thresholds for this project and do not represent official medical classifications.

## 🎓 Learning Outcomes

Through this project, I practiced:

- Loading CSV files with Pandas.
- Detecting and handling missing data.
- Creating new columns using NumPy.
- Grouping and aggregating data.
- Working with dates in Pandas.
- Creating line charts, bar charts, and heatmaps.
- Presenting data analysis results in a Jupyter Notebook.

## 👨‍💻 Author

Bhavya Shah

---

⭐ If you find this project useful, feel free to explore and improve it.

**Disclaimer:** This project is for educational purposes only. The results depend on the dataset and its limitations.
