
# Corporate Credit Rating Project

In this project I bring together the Rule 17g-7(b) reports of Moody's with Fundamental stock data for publicly listed companies in the US, acquired from SimFin.

I analyze the distribution of companies and liabilities over the different rating classes and the impact on the cost of capital.

As a result of the analyzed Data I train a machine learning model, using Extra Trees Classifier to predict the hypothetical Rating for unrated companies, to quickly and reliably asses their credit risk class.


## Authors

- https://github.com/GiancarloSanna


## Files

- Presentation.pptx:
The presentation of the results. Created as the final project for the Ironhack Data Analytics Bootcamp.


# Jupyter Notebooks
- 1.0 Preparing Rating Data.ipynb:
Extracting the rating data of the ca. 70.000 XBRL files published by Moody's on the SEC.gov page.

- 2.0 EDA and Data Cleaning.ipynb:
Cleaning and sighting the data for 3000 publicly traded Stocks.

- 3.0 Merging Data.ipynb:
Merging the different financial metrics from the financial statements.

- 4.0 Cleaning the Rating Data.ipynb:
Cleaning the rating data from notebook 1.

- 5.1 Finding matches with Rating Data.ipynb:
Using the difflib library in addition to some manual modifications to find matches in the Rating- and stock Data.

- 5.2 Matching with Rating Data.ipynb:
Merging the Stock and rating Data based on the pairings from 5.1

- 6.0 Descriptive analysis.ipynb:
Anylysing the combined data to find insights about the distribution and impact of Ratings.

- 7.0 Modelling.ipynb:
Creating the machine learing model.
I try out different models and enhance the result by feature engineering and Hyperparameter search.
## Conclusion

The Analysis showed, that the sum borrowed by invesment grade companies is extremely disproportionate considering their share of the total companies.

Furthermore the effect of a rating share below Baa has a way higher than expected impact.

The modeling has shown to be reliable even on companies, that were not available during the modelling process. Typically they end up in the range of +-1 rating stage. More testing will be needed concerning the rating of classes on the higher and lower end as the data available there was sparse.
## Data sources

Rating Data: https://www.sec.gov
Stock Data: https.//www.simfin.com


Ebay Logo: https:www.ebay.com Press Kit
