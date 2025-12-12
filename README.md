# CSUN COMP 641

## Group Members: Damir Kozhamkulov, Lucas Troutman, Diego Arteaga, Cody Laurie

## Project Description

This is a group project for CSUN Comp641 our goal is to build a classification model for CAASPP data involving school budget information

### Datasets Used

1. **CAASPP (California Assessment of Student Performance and Progress)**:

   - [Download Link](https://caaspp-elpac.ets.org/caaspp/researchfiles/sb_ca2024_1_csv_v1.zip)
   - This dataset provides student performance data for California schools.

2. **LAUSD Schools Geographic Information**:

   - [Explore Dataset](https://geohub.lacity.org/datasets/schools-lausd/explore?location=34.011807%2C-118.403498%2C9.30&showTable=true)
   - This dataset includes geographic and demographic information about schools in the Los Angeles Unified School District.

3. **LAUSD School Budget and Spending (Budget To Actual 2023-24)**:
   - [Explore Dataset](https://budgettransparency.lausd.net/school-budget)
   - This dataset provides detailed information on school budgets and spending for the 2023-24 academic year.

---

## How to Run the Code

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Damirchik11/Comp641.git
   cd Comp641
   ```

2. **Set Up the Environment**:
   - Ensure you have Python 3.8 or higher installed.
   - Install the required packages using `pip`:
     ```bash
     pip install -r requirements.txt
     ```
3. **Run the Jupyter Notebooks**:

   - Open the Jupyter Notebook server:
     ```bash
     jupyter notebook
     ```
   - Open and execute the following notebooks in order:
     - `EDA/--`: For exploratory data analysis.
     - `Final Project.ipynb`: For data preprocessing, model training, and evaluation.

4. **Outputs**:
   - The notebooks will generate metrics, visualizations, and insights related to the classification models.

---

## Required Environment and Package Setup

- **Python Version**: 3.8 or higher
- **Required Libraries**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - `jupyter`

---

## Project Structure

```
Comp641/
├── EDA/                              # Folder containing exploratory data analysis files
│   ├── Damir_EDA_Analysis.ipynb      # Exploratory data analysis by Damir
│   ├── Diego_EDA_Project_Edulytix.ipynb  # Exploratory data analysis by Diego
│   ├── project_eda.ipynb             # General exploratory data analysis
├── Final Project.ipynb               # Main notebook for model training and evaluation
├── README.md                         # Project documentation
├── school_funding_performance_clean.csv  # Cleaned dataset for analysis
├── school_usable_columns.csv         # Dataset with selected usable columns
├── sb_ca2024entities_csv.txt         # Raw CAASPP data file
├── df_3_4_inner (1).csv              # Additional dataset for merging
```

---
