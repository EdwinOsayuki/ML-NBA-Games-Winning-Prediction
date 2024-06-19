# ML-NBA-Games-Winning-Prediction

# Project Overview

In this project, we'll predict who will win basketball games in the NBA.  We'll start by web scraping NBA box scores.  We'll read in and clean the html using BeautifulSoup.  Then we'll parse the box scores into pandas DataFrames that we can use for machine learning.  Then we'll do feature selection to identify good predictors, and train a machine learning model to make predictions.  We'll end by computing rolling predictors and improving the model.

This is a complete end-to-end project, and we'll be using web scraping, data cleaning, and machine learning.

**Project Steps**

* Scrape standings and box score data
* Clean up html with BeautifulSoup
* Parse the box scores to get a DataFrame
* Run feature selection to identify predictors
* Train an ML model
* Compute rolling predictors to improve the model



File overview:

* `get_data.ipynb` - download the box scores from basketball reference.
* `parse_data.ipynb` - clean the data to get a pandas DataFrame.
* `predict.ipynb` - make predictions using machine learning

# Prerequisites

To complete this project, you'll need to have a good understanding of:

* Python syntax, including functions, if statements, and data structures
* Data cleaning
* Pandas syntax
* Using Jupyter notebook

You'll also need to know the basics of machine learning.



# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * scikit-learn
    * beautifulsoup4
    * playwright

## Data

We'll download our dataset from Basketball Reference.  

* You can find the pre-scraped data [here](https://drive.google.com/uc?export=download&id=10uPrEUqhe1uxShKiiZciRJViYqhJcre6) if you don't want to run the code.
* If you only want to do the second part of this project (prediction), you can download the csv file of box scores [here](https://drive.google.com/uc?export=download&id=1YyNpERG0jqPlpxZvvELaNcMHTiKVpfWe).
