Introduction to Matplotlib

What is Matplotlib?
    Matplotlib is one of the most widely used python library for data visualization. It helps cover raw data into meaningful graphical representation such as charts and plots.

    Data visualization is important because humans understand patterns, trends, and relationships much faster through graph than data in table.

    Matplotlib is commonly used in
    * Data Science
    * Machine learning
    * Business Analytics
    * Scientific Computing
    * Exploratory Data Analysis(EDA)

    It works very well with other Python libraries like NumPy and Pandas.

Why Data Visualization is important?
        When working with large dataset, looking at raw number can be difficult. Visualization help us quickly understand what data is telling us.

    Example:
    Day         sales
    Monday      200
    Tuesday     250
    Wednesday   400

    Instead of reading numbers, a chart immediately shows the trends of sales increasing

Benefits of visualization
1. Identify trends in data
2. Detect outliers or anomalies
3. Understand relationship between variables
4. communicate insights clearly
5. Support data-driven decision making

Visualization is key step in Exploratory Data Analysis(EDA) in data science.

Type of visualization in Matplotlib
plot type      Use case
Line Plot      Trends over time
Bar chart      compare categories
Scatter Plot   Relationship between variables
Histogram      Distribution of data
Pie Chart      Proportions
Box plot       Outliers and distributions


Matplot Architecture:

User Interface
    ↓
Pyplot API
    ↓
Object-Oriented API
    ↓
Backend Layer

1. Backend Layer:
Is responsible for rendering the visulaization
It determines how plot will apper 
- on screen 
- In a notebook
- Saved as a file

2. Artist Layer
Everything in Matplot is artist

Examples of Artists:
- Figure
- Axes
- Lines
- Text
- Labels
- Legends

These elements together build the complete visualization.

3. Pyplot Layer
The pyplot module provides a simple interface for creating plots.

example:

import matplotlib.pyplot as plt

plt.plot([1,2,3],[4,5,6])
plt.title("Simple Plot")
plt.xlabel("X Axis")
plt.ylabel("Y Axis")

plt.show()


Important concepts:
Figure: The figure is entire canvas where plots are drawn
Figure = Whole page

Axes: Represents actual plotting area inside the figure
Axes=Graph area

fig, ax = plt.subplots()
ax.plot([1,2,3],[4,5,6])

fig = Figure
ax = axes
