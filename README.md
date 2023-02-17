# Financial Data Project
End Goal: Create an app that can help you decide which stocks to buy and sell specific to Intel and Apple.

### Step 1: Find Data

1. **Huge Stock Market Dataset (Kaggle) Evaluation:** The dataset has an extensive amount of data (in terms of time) for both Apple and Intel which is hard to find on the internet. However, one limitation to this dataset is that the number of features is quite limited. I'll need to merge other datasets with this one if this serves as my base dataset so I have more information about each datapoint. Also note that the data is not updated which is a little annoying... if there is a dataset that has more recent data, then I would choose that over this.

2. **Stock Market Dataset (Kaggle) Evaluation:** This dataset is better than the Huge Stock Market Dataset because it has more recent data and also provides a script with which you can renew the data that you have. Similar to the Huge Stock Market Dataset, however, this dataset has only a limited number of features which only describe the stock value and not the company itself at the time. If this serves as the base dataset, we'll need to get more data from outside about each companies' revenue, fair value, etc.

3. **S&P 500 Stock Dataset (Kaggle) Evaluation:** The dataset did not need to be tested because it is not as extensive as the one offered by the Stock Market Dataset due to its short range of datapoints from 2013 to 2018. Additionally, this dataset has the same features as the Stock Market Dataset so it doesn't serve any benefit.

4. **New York Stock Exchange (Kaggle) Evaluation:** This dataset did not need to be tested because similar to the S&P 500 Stock Dataset, its timeline is very small, merely from 2010 to 2016. One thing that is useful in this dataset is that it provides a file that shows metrics extracted from annual SEC 10K fillings. However, there are probably more extensive datasets than this that cover the SEC 10K fillings.

5. **AMEX, NYSE, NASDAQ Stock Histories Dataset (Kaggle) Evaluation:** The dataset was not tested but it is extensive as it covers multiple indexes of the stock market. However, one major problem with it is that the dataset contains extremely recent data - just the last 2-3 years. Due to this, the dataset does not serve a strong purpose for this project.