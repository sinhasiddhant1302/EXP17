# **AIM:**

To study different data visualization techniques using Matplotlib and Seaborn including line charts, bar charts, histograms, and scatter plots.

---

# **THEORY :**

* **pd.DataFrame():** Creates a structured dataset for visualization. 

* **display():** Displays the dataset in tabular format. 

* **plt.plot():** Creates a line chart to show trends over time or categories. 

* **marker:** Adds symbols (like dots or squares) at data points in line charts. 

* **plt.xlabel() / plt.ylabel():** Labels the x-axis and y-axis respectively. 

* **plt.title():** Sets the title of the graph. 

* **plt.show():** Displays the plotted graph. 

* **plt.figure(figsize):** Sets the size of the graph (width and height). 

* **color:** Specifies color of plot elements. 

* **label:** Adds legend labels for multiple plots. 

* **plt.legend():** Displays legend in the graph. 

* **plt.bar():** Creates bar charts for comparison of values. 

* **edgecolor:** Adds border color to bars. 

* **plt.grid():** Adds grid lines for better readability. 

* **bar.get_height():** Retrieves height of each bar in bar chart. 

* **plt.text():** Adds text labels on graph elements. 

* **np.arange():** Generates evenly spaced numeric values for plotting positions. 

* **plt.xticks():** Sets custom labels on x-axis. 

* **plt.hist():** Creates histogram to show frequency distribution. 

* **bins:** Defines number of intervals in histogram. 

* **np.mean():** Calculates mean value for reference line in histogram. 

* **plt.axvline():** Draws a vertical line (e.g., mean line) on graph. 

* **plt.scatter():** Creates scatter plot to show relationship between variables. 

* **List comprehension (colors):** Assigns colors dynamically based on conditions. 

* **sns.lineplot():** Creates advanced line plots using Seaborn. 

* **sns.barplot():** Creates bar plots with statistical aggregation. 

* **sns.histplot():** Creates histogram using Seaborn with better styling. 

* **sns.scatterplot():** Creates scatter plots using Seaborn. 

* **errorbar=None:** Removes error bars from Seaborn plots. 

* **Data visualization:** Helps represent data graphically for better understanding and analysis.

* # Data Visualization: Graph Types and Usage

This document provides a summary of the different types of graphs used in the data visualization experiment, along with their descriptions and best use cases.

## Summary Table

| Graph Type | Description | Best Use Case |
| :--- | :--- | :--- |
| **Line Chart** | Displays data points connected by straight lines to show how a variable changes. | Ideal for showing **trends over time** or continuous sequences (e.g., Study hours throughout a week). |
| **Bar Chart** | Uses rectangular bars where the height or length is proportional to the values they represent. | Best for **comparing quantities** across different discrete categories (e.g., Marks obtained on different days). |
| **Grouped Bar Chart** | A variation of the bar chart where multiple bars are placed side-by-side for each category. | Used to **compare multiple metrics** simultaneously across the same categories (e.g., Comparing Study Hours vs. Marks). |
| **Histogram** | Represents the frequency distribution of a single numerical variable by grouping data into "bins." | Used to understand the **distribution and spread** of data (e.g., Identifying the frequency of specific mark ranges). |
| **Scatter Plot** | Uses individual dots to represent values for two different numeric variables on an X and Y axis. | Used to detect **correlations, patterns, or relationships** between two variables (e.g., Relationship between Study Hours and Marks). |
| **Conditional Scatter Plot** | A scatter plot where data points are color-coded based on a third categorical variable. | Used to visualize how a relationship differs across **different sub-groups** (e.g., Relationship between study/marks specifically for 'Pass' vs 'Fail' students). |

---

## Detailed Descriptions

### 1. Line Chart
The line chart is the most basic and commonly used plot. It is particularly effective for "Time Series" data. By observing the slope of the lines, one can quickly identify whether a metric is increasing, decreasing, or remaining stable. In the experiment, it was used to track the trend of study hours over a 5-day period.

### 2. Bar Chart
Bar charts are excellent for emphasizing the individual values of different categories. Unlike line charts, which imply a connection between points, bar charts treat each category as a distinct entity. Adding grid lines on the Y-axis (as seen in the experiment) helps in precise value reading.

### 3. Histogram
While a bar chart compares categories, a histogram visualizes the underlying frequency distribution of a continuous dataset. It helps in identifying whether the data is "Normally Distributed," skewed, or contains outliers. The experiment utilized a "Mean Line" overlay to show the center of the data relative to the distribution.

### 4. Scatter Plot
Scatter plots are essential for exploratory data analysis. They help in identifying:
* **Positive Correlation:** Both variables increase together.
* **Negative Correlation:** One variable increases while the other decreases.
* **No Correlation:** Points are scattered randomly.
The experiment further enhanced this by using colors to represent results (Red for Fail, Green for Pass), adding a third dimension of data to a 2D plot.

---

# **CONCLUSION :**

In this experiment, we explored different types of data visualization techniques using Matplotlib and Seaborn. Various plots such as line charts, bar charts, histograms, and scatter plots were created to analyze trends, comparisons, and relationships. Visualization makes data easier to interpret and helps in better decision-making. These tools are essential for effective data analysis and presentation.

---
