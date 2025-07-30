#  Data Exploration and Visualization with Pandas, Matplotlib & Seaborn

This project demonstrates the essential steps in loading, inspecting, and visualizing a dataset using Python libraries such as **pandas**, **matplotlib**, and **seaborn**. It is ideal for beginners in data science and data analysis.

---

## Tools and Libraries Used

- **Python 3**
- **Pandas** – For data loading and manipulation
- **Matplotlib** – For basic plotting
- **Seaborn** – For enhanced data visualization

---

##  Dataset

> A sample dataset (synthetic_asthma_dataset.csv) is used to perform exploratory data analysis.  
Replace the dataset path with your own dataset as needed.

---

##  Tasks Performed

###  Data Loading and Inspection

- Load the dataset using `pandas.read_csv()`
- Display:
  - The shape of the dataset
  - Column names
  - First few rows using `.head()`
- Summary of dataset using:
  - `.info()` — data types, missing values
  - `.describe()` — statistical summary

###  Data Visualization

- **Scatter Plot**  
  Show relationships between selected numerical features using `seaborn.scatterplot()` or `plt.scatter()`.

- **Histograms**  
  Show the distribution of feature values using `df.hist()` or `sns.histplot()`.

- **Box Plots**  
  Identify outliers in the data using `seaborn.boxplot()`.

---


