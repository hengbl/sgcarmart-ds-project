# sgcarmart-ds-project
My dad was recently looking into the used luxury sedan car market to scour for an affordable yet reliable option. So I decided to do a data analysis of the cars in the market and find out what are the brands available and how they are being priced. Since the used car market in Singapore is very fast moving and changing, I could not find any readily available dataset online. Hence I decided to scrape my own data from sgcarmart.

## 1) Web-scraping
I am utilising BS4 from beautifulsoup to help me scrape the data as it is a fast and reliable library for web-scraping. I will be scraping the first 1000 car listings as of 11 Jan 2023. The information of the cars are the listing name, price, depreciation, mileage, engine capacity, registration date and number of previous owners. They will then be stored in the csv file (sg_used_cars.csv). 

## 2) Data Cleaning
The data that I have scraped are very messy with alot of null values, duplicated rows and the columns are in inconsistent data type. After cleaning up the data, I used feature engineering to create new columns that are useful for my analysis. The new data is then saved to a new csv file (cleaned_cars.csv).
