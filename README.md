# pandas-and-polars
This repo contains some notebooks I created to play around with pandas and polars. 

The dataset used is the Chicago Crimes dataset from the Chicago Police Department. Downloaded on 30 Aug 2022 - Has records from Jan to Aug 2022

The dataset can be downloaded from [here](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2)

The dataset is also available in the repo as a CSV file.

## Pandas
[pandas_performance.ipynb](pandas_performance.ipynb) explains some of the performance issues with pandas and how to overcome them using the new pandas datatypes like Int64, StringDtype, and CategoricalDtype, etc. It also shows examples of writing effective and elegant pandas code using method chaining. 

[pandas_arrow.ipynb](pandas_arrow.ipynb) gives a quick intro to the pandas 2.0 features and then compares the performance of pandas numpy vs arrow engines. 

## Polars
[polars.ipynb](polars.ipynb) gives a very quick intro to polars. 
