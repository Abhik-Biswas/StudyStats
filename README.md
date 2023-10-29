# StudyStats
Repository containing the code for a web application, designed to be a one-stop place for beginners in statistics

# Streamlit Data Analysis App - StudyStats

This is a Streamlit application for data analysis that allows you to perform various data analysis tasks on a dataset. You can upload a dataset in CSV format and explore its numerical and categorical columns, visualize data distributions, and perform hypothesis testing on numerical columns.

## Table of Contents
1. [Installation of Required Dependencies](#installation)
2. [Usage](#usage)
3. [Features](#features)
4. [Documentation](#documentation)
    - [Uploading Data](#uploading-data)
    - [Exploring Numerical Columns](#exploring-numerical-columns)
    - [Data Distribution](#data-distribution)
    - [Numerical Summary](#numerical-summary)
    - [Correlation Analysis](#correlation-analysis)
    - [Multivariate Analysis](#multivariate-analysis)
    - [Categorical Data Analysis](#categorical-data-analysis)
    - [Hypothesis Testing](#hypothesis-testing)
5. [Contributing](#contributing)
6. [License](#license)

## Installation <a name="installation"></a>

To run this Streamlit app, you'll need to have Python installed on your system. You can then install the required packages using pip:

```bash
pip install numpy pandas streamlit plotly statsmodels scipy seaborn
```

## Usage <a name="usage"></a>

To run the app, use the following command:

```bash
streamlit run your_app_name.py
```

Replace `your_app_name.py` with the name of the Python script containing the code provided.

## Features <a name="features"></a>

- Upload a dataset in CSV format.
- Explore and select numerical columns for further analysis.
- Visualize data distributions.
- Calculate the five-point summary of numerical columns.
- Conduct correlation analysis.
- Perform multivariate analysis on selected numerical columns.
- Analyze categorical data with box plots or violin plots.
- Perform hypothesis testing on numerical columns.

## Documentation <a name="documentation"></a>

### Uploading Data <a name="uploading-data"></a>

1. Start by uploading your dataset in CSV format. Click the "Upload Dataset" button and select the file you want to analyze.

### Exploring Numerical Columns <a name="exploring-numerical-columns"></a>

2. After uploading the dataset, the app will display the first 50 rows of the dataset and list the detected numerical columns.

3. You can choose which numerical columns you want to further process by using the checkboxes on the sidebar.

### Data Distribution <a name="data-distribution"></a>

4. To check the distribution of data, select a numerical column from the dropdown menu and enter the bin size for the distribution plot.

### Numerical Summary <a name="numerical-summary"></a>

5. Select a numerical column to display a five-point summary, including minimum, Q1, median, Q3, and maximum values.

6. Choose the type of correlation analysis (Pearson, Kendall, or Spearman) and view the correlation matrix heatmap for selected numerical columns.

### Multivariate Analysis <a name="multivariate-analysis"></a>

7. For multivariate analysis, select up to 4 numerical columns from the sidebar checkboxes. The app will create scatter plots for the selected columns.

### Categorical Data Analysis <a name="categorical-data-analysis"></a>

8. Analyze categorical data by selecting a categorical column for the X-axis and a numerical column for the Y-axis. You can also choose a categorical variable for color, and select the chart type (boxplot or violinplot).

### Hypothesis Testing <a name="hypothesis-testing"></a>

9. Perform hypothesis testing on numerical columns. Choose the type of test (Z-Test, T-Test, Chi-Square Test, F-Test, or 2-Sample Z-Test).

10. Select the columns for testing and specify custom test values if needed.

11. The app will display visualizations of the test results, including critical regions and test statistics.

12. You can interpret the results and decide whether to accept or reject the null hypothesis based on the p-value and significance level.

## Contributing <a name="contributing"></a>

If you'd like to contribute to this Streamlit data analysis app, please feel free to fork the repository, make your changes, and submit a pull request.
