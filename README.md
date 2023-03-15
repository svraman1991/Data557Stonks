# Data557Stonks
The repository for our Data 557 Winter quarter final project

# Steps to run:
1. Clone the repo
2. Run the Bhavcopy_Scraping.ipynb file in order to scrape the daily archives from the NSE (Change the folder paths as per requirement)
3. Run the Assumption_tests_Welch_test.ipynb file in order to compile the results for the tests for the assumptions of skewness and kurtosis.
   The file also performs the Welch-t-test between individual stocks and the Nifty50 index. 
4. Run DATA557_DataPrep (Change the folder paths as per requirement).
5. Run DATA557_EDA for Exploratory Data Analysis (Change the folder paths as per requirement). 
6. Run DATA557_Correlation to run the correlation tests (Change the folder paths as per requirement).
7. Run DATA557_LinearRegression to run the linear regression for all stocks (Change the folder paths as per requirement).

## Outcomes after running each Jupyter Notebook:

1. Bhavcopy_Scraping.ipynb will return the daily archives from the NSE in the .csv format.
2. Assumption_tests_Welch_test.ipynb will run the assumption tests for whether skewness and/or kurtosis can be neglected.
   Also runs the welch-t-test between the individual stocks and the Nifty50 index.
3. The DATA557_Dataprep.ipynb file will perform data preprocessing on the daily archives in order to make the data usable for further analysis.
4. The DATA557_EDA.ipynb file will perform the EDA for the top 5 stocks (Graphs for Skewness, kurtosis, and autocorrelation).
5. The DATA557_Correlation.ipynb file will perform the correlation and hypothesis tests on the correlation(s).
6. The DATA557_LinearRegression.ipynb file will perform linear regression on the indicators(predictors) to predict the price returns(response).
