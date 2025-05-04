##BIG DATA PROGRAMMING PROJECT

In order to comprehend travel behavior, trends, and forecasts, this research analyzes mobility trends using historical trip data. The data covers a range of travel classifications, population staying at home, and excursions over varying distances. To get insight into travel trends, the analysis makes use of data pre-processing, machine learning models, and data visualization approaches.

##PROJECT STRUCTURE

##1. DATA PRE-PROCESSING
1.a To get datasets ready for analysis, they must be cleaned and categorized.
1.b Address missing values, eliminate duplication, and make sure column names are consistent.

##2. DATA CATEGORIZATION
2.a Sorts journeys into short-, medium-, and long-distance categories.
2.b Based on population statistics, population behavior categorization divides data into those who are traveling and those who are staying at home.

##3. OPTIMIZATION
Dask parallel processing, as opposed to conventional Pandas-based sequential processing, can increase performance and decrease computing time for huge datasets.

##4. MODELLING
4.a Train and assess several regression models, such as Random Forest, Polynomial Regression, and Linear Regression.
4.b Using past data, models are used to forecast travel behavior.

##5. DATA ANALYSIS
5.a Examine patterns of travel behavior over time, taking into account seasonal variances and weekly mobility patterns.
5.b statistical study, including correlations between various variables (e.g., population staying at home and travels taken).

##6. MODEL TESTING
6.a To verify the chosen models, divide the dataset into training and testing sets.
6.b Use measures like Mean Absolute Error (MAE) and R2 score to assess a model's performance.

##7. DATA VISUALIZATION
7.a To visually depict the data and highlight important insights, use a range of charts and graphs, such as bar charts, pie charts, scatter plots, histograms, and KDE plots.
7.b By highlighting patterns and trends, visualizations facilitate the interpretation of data.
   

##PROJECT WORK OVERFLOW
##1. DATA PRE PROCESSING
1.1 After missing values are addressed, duplicates are eliminated, and pertinent columns are chosen, the dataset is cleaned and organized.
1.2 The format of date columns is changed to suit time-series analysis.

##2. DATA CATEGORIZATION
2.1 Trips are divided into three categories: short, medium, and long-distance.
2.2 There are two types of population behavior: those who travel and those who stay at home.

##3. ANALYZING DATA
3.1 The total number of journeys and the number of persons staying at home are calculated.
3.2 Seasonal and temporal trends in travel behavior are identified by analyzing weekly mobility patterns.

##4. MODELLING
4.a To match historical data and forecast travel trends, a variety of regression models are employed, including Random Forest, Polynomial Regression, and Linear Regression.
4.b Metrics like the R2 score and Mean Absolute Error (MAE) are used to assess the correctness of the model.

##5. OPTIMIZATION
In comparison to serial processing with Pandas, Dask for parallel processing optimizes the pace of data processing, resulting in a significant reduction in computing time and an improvement in performance.

##6. VISUALIZATION
6.a Trip data, including distribution and trends over time, are visualized using bar charts, pie charts, histograms, and KDE plots.
6.b Scatter plots show particular dates when a lot of people traveled within a given distance range.
##KEY VISUALIZATION
##BAR CHART: The number of travelers by distance category is compared in a bar chart.
##PIE CHART: The percentage of travelers within each distance range is displayed in a pie chart.
##HISTOGRAMS:The distribution of travelers by distance category is shown by the histogram.
##KDE PLOT: Examines the frequency distributions of short and lengthy trips.
##SCATTER PLOT: Show the dates on which over 10 million people traveled within particular ranges.

##REQUIREMENTS
1.Python 3.x
2.Pandas
3.Dask
4.Matplotlib
5.Seaborn
6.Scikit-learn
7.NumPy
8.Statsmodels

##TO INSTALL REQUIRED PACKAGES
pip install pandas dask matplotlib seaborn scikit-learn numpy statsmodels

##DATASETS USED FOR BIG DATA PROGRAMMING PROJECT 
1. Trips_by_Distance.csv 
2. Trips_Full Data.csv

