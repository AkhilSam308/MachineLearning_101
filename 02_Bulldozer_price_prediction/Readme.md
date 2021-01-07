
# MachineLearning_Basics

This project is a sample (proof of concept) ML project (done as a part of the course Zero to Mastery ML) for building a model capable of predicting bulldozer sale price from their charecterstics and previous sale records using Machine Learning

### Problem Definition 

The problem we're trying to solve in this example project is: 

>How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers have been sold for?

### Data 

The data used in this project is from the *Blue Book for Bulldozers, 2012* competetion.  The data can be downloaded via [Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data). The data at hand for this project is time-series data. It is historical sales data of bulldozers. Including things like, model type, size, sale date and more.

There are 3 datasets:

- Train.csv - Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes, including  SalePrice which is the target variable).
- Valid.csv - Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with the same attributes as Train.csv).
- Test.csv - Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing the SalePrice attribute, as this is what we'll be trying to predict).

Libraries used in this project:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn (sklearn)

Model used: Random Forest Regressor

The project was written on windows 32 bit with Python 3.8.3
