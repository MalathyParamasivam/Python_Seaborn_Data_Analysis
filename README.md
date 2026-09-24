# Python Seaborn Data Analysis

## Project Overview
This project focuses on exploring, cleaning, analyzing, and visualizing the Seaborn **Taxis dataset** using Python. The project covers missing value handling and different visualization techniques to understand patterns and relationships in the data.

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib

## Dataset
The **Taxis dataset** is obtained from the Seaborn library using:

```python
import seaborn as sns
df = sns.load_dataset("taxis")
```

## Data Exploration & Cleaning
The dataset was explored using:
- `head()`
- `tail()`
- `info()`
- `shape`
- `dtypes`
- `isnull().sum()`

Missing values were identified and handled using **mode imputation** for categorical columns such as:
- Payment
- Pickup Zone
- Dropoff Zone
- Pickup Borough
- Dropoff Borough

## Data Analysis & Visualization

### Line Plot
Visualized **fare over time** using pickup timestamp and fare.

### Bar Chart
Displayed the **total fare for each pickup borough** using `groupby()` and `sum()`.

### Pie Chart
Showed the **distribution of trips by payment method** using `value_counts()`.

### Histogram
Visualized the **distribution of taxi trip distances**.

### Box Plot
Analyzed the **distribution of tips across pickup boroughs** and identified the spread and potential outliers.

### Count Plot
Displayed the **number of trips in each pickup borough**.

### Scatter Plot
Analyzed the relationship between **distance and fare**, with pickup borough represented using `hue`.

### Heatmap
Displayed the **correlation between numerical variables** such as distance, fare, tip, tolls, and total.

### Pair Plot
Visualized pairwise relationships between:
- Distance
- Fare
- Tip
- Total

Pickup zones were used as `hue` for comparison.

### Violin Plot
Visualized the **distribution of fare for different payment methods**.

## Key Concepts Practiced
- Data exploration
- Data cleaning
- Missing value handling
- Categorical and numerical data analysis
- GroupBy and aggregation
- DateTime conversion
- Data visualization
- Correlation analysis
- Distribution analysis
- Relationship analysis

## Learning Outcome
This project helped develop practical skills in **Pandas, Seaborn, and Matplotlib** and improved understanding of how data cleaning and visualization can be used to identify patterns, distributions, relationships, and trends in a dataset.

## Author
**Malathy Paramasivam**

## Skills Practiced
`Python` `Pandas` `NumPy` `Seaborn` `Matplotlib` `Data Cleaning` `Data Analysis` `Data Visualization`

