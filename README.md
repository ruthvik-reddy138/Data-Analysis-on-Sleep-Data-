# Exploratory Data Analysis on Sleep Data

## Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset containing health and sleep statistics. The objective is to analyze patterns, correlations, and trends affecting sleep quality.

## Dataset
- **File Name**: Health_Sleep_Statistics.csv
- **Features**:
  - `Age`: Age of individuals.
  - `Sleep Quality`: Measure of sleep quality.
  - Additional features relevant to health and sleep patterns.

## Requirements
To run the notebook, install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Methodology
1. **Data Loading & Cleaning**
   - Read CSV file and inspect structure.
   - Handle missing values and duplicates.
   - Drop unnecessary columns (e.g., user_id).
   
2. **Exploratory Data Analysis**
   - Summary statistics (`describe()`, `info()`).
   - Visualization using **Matplotlib** & **Seaborn** (Bar plots, Correlation heatmaps, etc.).

3. **Correlation Analysis**
   - Examines the relationship between **Age** and **Sleep Quality**.
   - Uses `corr()` to compute correlation coefficients.

4. **Linear Regression Model**
   - Builds a predictive model using **scikit-learn**.
   - Fits a **Linear Regression** model to predict **Sleep Quality** based on **Age**.
   - Visualizes regression results.

## Usage
Run the Jupyter Notebook:

```bash
jupyter notebook EDA_on_Sleep_Data.ipynb
```

Follow the step-by-step analysis within the notebook to understand sleep patterns and predictions.

## Results & Insights
- Identified correlation trends between **Age** and **Sleep Quality**.
- Built a simple **Linear Regression Model** for predictive analysis.
- Found key insights regarding sleep patterns through visualizations.

## Contribution
Feel free to fork the repository, make improvements, and submit pull requests.

## License
This project is open-source and available under the MIT License.

