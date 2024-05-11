# Data Analytic Learning (3)
# Basic of  visualization
## 4 Reason use chart
### 1) Comparison
A comparison chart is a visual tool used to contrast various sets of variables, facilitating the identification of differences and similarities. By plotting variables on a chart, it unveils relationships, patterns, and trends, aiding in the process of making well-informed decisions.

##### - Bar Chart Vertical
The bars are plotted along the y-axis (vertical axis), with each bar representing a category or variable. The height of each bar corresponds to the value of the variable it represents. Vertical bar charts are effective for comparing categories with long labels or when there are many categories to display. They are commonly used for discrete data. Example

![Screenshot (887)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/960c104b-6d3d-4304-99fa-4c696d61b037)

##### - Bar Chart Horizontal
A horizontal bar chart plots bars along the x-axis, with each bar representing a category and its length indicating the variable's value. It's ideal for lengthy category labels or emphasizing differences in magnitude between categories. Example:

![Screenshot (910)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/44605fe5-a5cc-4e42-a69e-cd0265cd2e2b)

##### - Line Chart
A line chart shows data points connected by straight lines, each representing a variable's value at a specific time or category. It's great for displaying trends over time or showcasing variable relationships.Example:

![Screenshot (889)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/98cc4564-4618-4b19-8b1a-6a0e423b6825)

##### - Multiple Line Chart
 A type of line chart that displays multiple lines on the same graph to compare trends or relationships between two or more categories.Example:

![Screenshot (911)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/846adeb1-2753-4acc-ab84-a44e9014865b)

### 2) Composition
Charts help in illustrating the composition of a whole by breaking it down into its constituent parts. Pie charts, stacked bar charts, and treemaps are examples of charts that can effectively depict composition

#### - Stacked Bar Chart (Composition & Comparison)
A stacked bar chart shows multiple bars per category, divided into segments for different sub-categories. Each bar's height represents the total category value, while segments show each sub-category's contribution. It's great for displaying both category totals and compositions. Example:

![Screenshot (912)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/675829e4-d257-4233-aaf4-3f26f0211c1a)


#### - Stacked 100% Bar Chart (Composition & Comparison)
A Stacked 100% Bar Chart combines composition and comparison. Each bar represents 100% of a category's value, with segments showing sub-categories. Focus on contribution on each components, canbe use over time(few period). Example:

![Screenshot (913)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/07db0e33-5702-468d-b643-69441356fb75)


#### - Pie Chart
A pie chart divides a circle into slices to show numerical proportions, representing how categories contribute to a whole. It's effective for visualizing 100% proportions or percentages.Example:

![Screenshot (914)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/382ae317-a132-406f-8122-97bcaef6d329)


#### - Tree Map Chart
A treemap chart shows hierarchical data with rectangles, sizes reflecting attributes. It's for visualizing hierarchy composition quickly. Example:

![Screenshot (915)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/f15b83c4-3626-44cb-82bd-21868b9d24f6)

### 3) Relationship (Scatter plot)
Charts can visualize relationships between variables, showing how changes in one variable correlate with changes in another. Scatter plots and line charts are commonly used for displaying relationships between variables. Example:

![Screenshot (916)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/7c4e32df-8567-423d-9de7-8866522c8c34)


### 4) Spatial (Map)
Certain types of charts, such as maps and spatial heatmaps, can represent data in a spatial context, showing variations or distributions across geographical regions. This is particularly useful for analyzing location-based data or patterns. Example: 

![Screenshot (917)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/b821c9e8-a37e-4d64-820c-f97f6737aeab)


# Data Analytic: Visualization Using Python
## Matloplib
This library provides various functions and tools for creating different types of plots and graphs, allowing users to visualize data in a clearer and easier-to-understand way.

## Seaborn
This library for creating statistical graphs with Python. It is built on top of matplotlib and tightly integrated with pandas data structures. Seaborn helps explore and understand data 

To import data visualization libraries like Matplotlib, Seaborn, or Plotly in Python, use the import statement: 

![Screenshot (909)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/a6919835-54e3-4033-bedc-4b0642a5b38b)

### Line Chart using Matloplib
Create data from the list created, after define the data then plot line chart using matloplib
![Screenshot (918)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/9a6901c3-df80-4384-9b77-a4bf753f38bd)

to better understand the graph and its purpose, add x-axis values

![Screenshot (919)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/844dfb4d-3f21-4809-9a7b-be98c94b4cde)

parameter 1 consists of an array containing x-axis points, while Parameter 2 comprises an array containing y-axis points. Label the x and y axis

![Screenshot (920)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/cad54978-7cc7-4c4a-8450-1b62c99d3ec4)

### Multiple Line Chart using Matloplib
Create data from the list created,

![Screenshot (922)_LI](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/6daf5f95-2442-4c58-b4ab-2ba22f4d9a1b)

After that plot multiple line chart. This involves generating two line plots through Matplotlib. We can add a legend which tells us what each line in our graph means. To understand what we are plotting, we can add a title to our graph.
code: 
plt.plot(years, apples)
plt.plot(years, tangerines)
plt.xlabel("Year")
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Bandung")
plt.legend(['Apples', 'Tangerines'])

result: 

![Screenshot (911)](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/134476980/b81af96d-a8ed-42a8-adb7-119e7c66f17b)

Example of darkgrid and white grid

Darkgrid: 
![darkgrid](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/101807673/3f5b3585-0a30-46be-941f-071baaacb74f)

whitegrid:
![whitegrid](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/101807673/ad5620e0-76ac-457a-8d4e-1831ebe83d45)


### Dataset Using Seaborn
Seaborn itself doesn't provide built-in datasets. It's a visualization library that works with data you provide.  However, there are a couple ways to get datasets to use with seaborn: Load an example dataset:  Seaborn does have a function called load_dataset that can download a small set of sample datasets from a public repository.  These are meant for documentation purposes and exploring how to use seaborn functions, not for substantial data analysis. You can find more info on how to use this function in the seaborn documentation

Example:
- ![SEABORNBAR](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/101807673/1d28ca31-3343-428d-a3da-af937476dab1)

### Histogram, Bins, and Range
A histogram is a powerful tool data analysts use to visualize the distribution of continuous data. Imagine you have a bunch of numbers representing things like heights, weights, or test scores. A histogram helps you understand how these values are spread out.
Here's how it works:
- Bins: Data analysts don't plot every single data point. Instead, they group the data points into ranges called bins. These bins act like buckets, where each bucket holds data points that fall within a certain range.
- Range: The range refers to the overall spread of your data. It's the difference between the highest and lowest values in your dataset. When creating bins, you consider the range to decide how wide each bin should be and how many bins you need.

Example:
![histogram](https://github.com/ghiyatsalkadzim/Data_Analyst_Week_3/assets/101807673/7d563f6e-2808-44ef-8271-dd94b3427c22)



