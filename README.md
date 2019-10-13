# Visualizing-Earnings-Based-On-College-Majors
Using matplotlib, pandas data structures and other python tools to visualize earnings in comparison to college degrees.

Introduction:-

We'll be working with a dataset on the job outcomes of students who graduated from college between 2010 and 2012. The original data on job outcomes was released by American Community Survey, which conducts surveys and aggregates the data. FiveThirtyEight cleaned the dataset and released it on their Github repo.

Each row in the dataset represents a different major in college and contains information on gender diversity, employment rates, median salaries, and more. 

Each row in the dataset represents a different major in college and contains information on gender diversity, employment rates, median salaries, and more. Here are some of the columns in the dataset:

1. Rank - Rank by median earnings (the dataset is ordered by this column).
2. Major_code - Major code.
3. Major - Major description.
4. Major_category - Category of major.
5. Total - Total number of people with major.
6. Sample_size - Sample size (unweighted) of full-time.
7. Men - Male graduates.
8. Women - Female graduates.
9. ShareWomen - Women as share of total.
10. Employed - Number employed.
11. Median - Median salary of full-time, year-round workers.
12. Low_wage_jobs - Number in low-wage service jobs.
13. Full_time - Number employed 35 hours or more.
14. Part_time - Number employed less than 36 hours.

Using visualizations, we can start to explore questions from the dataset like:

1. Do students in more popular majors make more money? Using scatter plots.
2. How many majors are predominantly male? Predominantly female? Using histograms.
3. Which category of majors have the most students? Using bar plots.

When we want to explore a new dataset by quickly creating visualizations, using tools like pyplot and matplotlib directly can be cumbersome. Thankfully, pandas has many methods for quickly generating common plots from data in DataFrames. Like pyplot, the plotting functionality in pandas is a wrapper for matplotlib. This means we can customize the plots when necessary by accessing the underlying Figure, Axes, and other matplotlib objects.

We'll explore how using the pandas plotting functionality along with the Jupyter notebook interface allows us to explore data quickly using visualizations.
We'll explore how to do these and more while primarily working in pandas. 
