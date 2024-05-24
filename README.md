# PRODIGY_DS_01

---

# World Population Data Analysis

This project aims to analyze world population data retrieved from the World Bank database. It utilizes Python libraries such as pandas, NumPy, Matplotlib, and Seaborn for data manipulation, visualization, and analysis.

## Overview

The dataset contains information about population statistics for various countries over multiple years. Key aspects of the analysis include:

- Extracting top and bottom 10 countries based on total population.
- Visualizing population trends over the years for selected countries.
- Analyzing male and female population distributions.

## Features

### Data Loading and Inspection

- The dataset is loaded into a pandas DataFrame for further processing.
- Basic information about the dataset such as shape, column names, and data types is inspected using `info()` and `describe()` functions.

### Data Preprocessing

- Irrelevant columns such as 'Series Name' and 'Country Code' are dropped from the DataFrame.
- Missing values are checked using `isna().sum()` function.

### Top and Bottom 10 Countries by Total Population

- Top 10 countries with the highest total population for the year 2022 are identified and visualized using bar plots.
- Similarly, bottom 10 countries with the lowest total population for the year 2022 are identified and visualized.

### Male and Female Population Analysis

- The dataset is filtered to extract male and female population data separately.
- Top and bottom 10 countries with the highest and lowest male and female populations for the year 2022 are identified and visualized.
- Stacked bar plots are used to compare male and female populations in the top and bottom 10 countries.

## Dependencies

- pandas
- NumPy
- Matplotlib
- Seaborn

## Usage

1. Clone the repository:

```
git clone https://github.com/your_username/world-population-analysis.git
```

2. Navigate to the project directory:

```
cd world-population-analysis
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Run the analysis script:

```
python analyze_population_data.py
```

## Acknowledgments

Special thanks to the World Bank for providing the dataset used in this analysis.

---
