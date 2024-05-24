This project conducts an exploratory data analysis on global startup funding using two datasets: funds.csv and funding_rounds.csv. The goal is to merge and clean the data, then extract and visualize key insights about startup funding trends. The steps involved in the project are as follows:

#### 1. Convert CSV Files to DataFrames: Load the funds.csv and funding_rounds.csv files into pandas dataframes for data manipulation and analysis.

#### 2. Merge DataFrames: Identify a common element between the two dataframes and merge them into a single dataframe.

#### 3. Clean Data:
* Remove irrelevant columns: 'id', 'source_url', 'source_description', and 'updated_at'.
* Display the number of null values in each column and the percentage of nulls per column.
* Replace all null values in 'raised_currency_code' with 'USD'.
* Eliminate the remaining null values from the dataset.
* Analyze Currency Distribution: Show the percentage distribution of different values in 'raised_currency_code'.

#### 4. Visualize Data:
* Create a subset excluding 'USD' and visualize it using a bar chart.
* Create a new subset filtering out all rows with funding amounts below 10M and visualize this subset with a histogram.
* Further filter the dataset for startups founded in the year 2000 using the contains() function.
* Visualize the funding amounts by currency type for startups founded in 2000.
* The project aims to identify patterns and trends in startup funding, providing valuable insights for stakeholders in the startup ecosystem.
