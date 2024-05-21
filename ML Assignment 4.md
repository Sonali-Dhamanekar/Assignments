1. What are the key tasks involved in getting ready to work with machine learning modeling?

Collecting Data: As you know, machines initially learn from the data that you give them

Preparing the Data: After you have your data, you have to prepare it

Choosing a Model

Training the Model

Evaluating the Model

Parameter Tuning

Making Predictions

2. What are the different forms of data used in machine learning? Give a specific example for each of them.

Data can come in many forms, but machine learning models rely on four primary data types. These include numerical data, categorical data, time series data, and text data.

Numerical data includes values that can be ordered and measured, such as age or income. Categorical data includes values that represent categories, such as gender or type of fruit. Data can be divided into training and testing sets


3. Distinguish:

1. Numeric vs. categorical attributes

2. Feature selection vs. dimensionality reduction

1. Numeric vs. categorical attributes

Categorical data refers to a data type that can be stored and identified based on the names or labels given to them. Numerical data refers to the data that is in the form of numbers, and not in any language or descriptive form. Also known as qualitative data as it qualifies data before classifying it.

2. Feature selection vs. dimensionality reduction

Feature Selection: Selects a subset of relevant features while keeping the original feature space intact. The focus is on identifying the most informative features for modelling. Dimensionality Reduction: Projects the data onto a lower-dimensional space by transforming the feature space.

4. Make quick notes on any two of the following:

  1. The histogram

  2. Use a scatter plot
  
  3.PCA (Personal Computer Aid)


1. The histogram

A frequency distribution shows how often each different value in a set of data occurs. A histogram is the most commonly used graph to show frequency distributions. It looks very much like a bar chart, but there are important differences between them.

WHEN TO USE A HISTOGRAM
Use a histogram when:

The data are numerical
You want to see the shape of the data’s distribution, especially when determining whether the output of a process is distributed approximately normally
Analyzing whether a process can meet the customer’s requirements
Analyzing what the output from a supplier’s process looks like
Seeing whether a process change has occurred from one time period to another
Determining whether the outputs of two or more processes are different
You wish to communicate the distribution of data quickly and easily to others

HISTOGRAM ANALYSIS
Before drawing any conclusions from your histogram, be sure that the process was operating normally during the time period being studied. If any unusual events affected the process during the time period of the histogram, your analysis of the histogram shape likely cannot be generalized to all time periods.
Analyze the meaning of your histogram's shape. 

2. Use a scatter plot

A scatter plot is a chart type that is normally used to observe and visually display the relationship between variables. The values of the variables are represented by dots. The positioning of the dots on the vertical and horizontal axis will inform the value of the respective data point; hence, scatter plots make use of Cartesian coordinates to display the values of the variables in a data set. Scatter plots are also known as scattergrams, scatter graphs, or scatter charts.

A scatter plot is a chart type that is normally used to observe and visually display the relationship between variables. It is also known as a scattergram, scatter graph, or scatter chart.
The data points or dots, which appear on a scatter plot, represent the individual values of each of the data points and also allow pattern identification when looking at the data holistically.
The most common use of the scatter plot is to display the relationship between two variables and observe the nature of such a relationship. The relationships observed can either be positive or negative, non-linear or linear, and/or, strong or weak.

Scatter Plot Applications and Uses
1. Demonstration of the relationship between two variables
The most common use of the scatter plot is to display the relationship between two variables and observe the nature of the relationship. The relationships observed can either be positive or negative, non-linear or linear, and/or, strong or weak.

The data points or dots, which appear on a scatter plot, represent the individual values of each of those data points and also allow pattern identification when looking at the data holistically.

2. Identification of correlational relationships
Another common use of scatter plots is that they enable the identification of correlational relationships. Scatter plots tend to have independent variables on the horizontal axis and dependent variables on the vertical axis. It allows the observer to know or get an idea of what the possible vertical value may be, provided there is information on the horizontal value.

3. Identification of data patterns
Data pattern identification is also possible with scatter plots. Data points can be grouped together based on how close their values are, and this also makes it easy to identify any outlier points when there are data gaps.

5. Why is it necessary to investigate data? Is there a discrepancy in how qualitative and quantitative data are explored?

Data allows organizations to measure the effectiveness of a given strategy: When strategies are put into place to overcome a challenge, collecting data will allow you to determine how well your solution is performing, and whether or not your approach needs to be tweaked or changed over the long-term.

Quantitative questions typically involve closed-ended responses where respondents choose from pre-determined options or provide numerical ratings. These questions focus on measurable aspects and generate numerical data. The analysis of quantitative data involves statistical techniques such as averages, percentages, correlations, and regression analysis. This type of analysis aims to identify patterns, relationships, and trends within the data.  

On the other hand, qualitative questions involve open-ended responses, allowing respondents to provide detailed and subjective information. These questions delve into individuals' experiences, opinions, beliefs, and perceptions. The analysis of qualitative data involves a process of coding and categorizing the responses, looking for recurring themes and patterns. It often involves techniques like content analysis, thematic analysis, or discourse analysis. 

6. What are the various histogram shapes? What exactly are ‘bin'?

There are different types of distributions, such as normal distribution, skewed distribution, bimodal distribution, multimodal distribution, comb distribution, edge peak distribution, dog food distribution, heart cut distribution, and so on.

Data binning is the process of organizing your data into a finite range of intervals. Those range of intervals are called “bins”.

Data binning, also known as “data bucketing”, is a data pre-processing technique used in machine learning and data mining to group continuous data values into discrete intervals or “bins.” Binning can serve multiple purposes, including reducing data errors by smoothing out fluctuations in the data, gaining insights 

7. How do we deal with data outliers?

Three main methods of dealing with outliers, apart from removing them from the dataset: 1) reducing the weights of outliers (trimming weight) 2) changing the values of outliers (Winsorisation, trimming, imputation) 3) using robust estimation techniques (M-estimation).

Treatment of outliers
Three main methods of dealing with outliers, apart from removing them
from the dataset:
1) reducing the weights of outliers (trimming weight)
2) changing the values of outliers (Winsorisation, trimming, imputation)
3) using robust estimation techniques (M-estimation).


8. What are the various central inclination measures? Why does mean vary too much from median in certain data sets?

There are three main measures of central tendency:

mode
median
mean

As the data becomes skewed the mean loses its ability to provide the best central location for the data because the skewed data is dragging it away from the typical value. However, the median best retains this position and is not as strongly influenced by the skewed values.

9. Describe how a scatter plot can be used to investigate bivariate relationships. Is it possible to find outliers using a scatter plot?

A scatterplot shows the relationship between two quantitative variables measured for the same individuals. The values of one variable appear on the horizontal axis, and the values of the other variable appear on the vertical axis. Each individual in the data appears as a point on the graph.

Yes it is possible to find outliers using a scatter plot.

10. Describe how cross-tabs can be used to figure out how two variables are related.

Cross tabulation is a method to quantitatively analyze the relationship between multiple variables. Also known as contingency tables or cross tabs, cross tabulation groups variables to understand the correlation between different variables. It also shows how correlations change from one variable grouping to another.
