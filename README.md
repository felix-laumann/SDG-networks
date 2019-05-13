# SDG dataset

This is a collecition of notebooks working with the data set available on [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/).

- [country_diaggregation](https://github.com/felix-laumann/SDG-dataset/blob/master/country_diaggregation.ipynb) splits data in separate `csv` files per country, and all other groupings. For all other information, including where to download the original data set, see the notebook. 

- [imputations](https://github.com/felix-laumann/SDG-dataset/blob/master/imputations.ipynb) imputes missing values in the data set either with a **weighted k nearest neighbour (w-kNN)** algorithm, if less than 9 measurements are available from the years 2000 to 2018, or with **Gaussian processes (GPs)**, if more than 9 measurements are available.

- [similarities](https://github.com/felix-laumann/SDG-dataset/blob/master/similarities.ipynb) computes the [distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between each unique pair of sub-indicators in all groupings.


## Direct downloads

- [original `csv` files](https://www.dropbox.com/sh/z54b8kgb7awpk56/AADGRnBd3ZH7unFwC9PnB8xaa?dl=0)

- [standardised `csv` files](https://www.dropbox.com/sh/5jiz4ytf7gzbdjy/AACOcMx5SE-xFmq5AZSOjIuma?dl=0)

- [standardised `csv` files with imputations](https://www.dropbox.com/sh/fgwpxet2heuf9gd/AACshLajFaBDb13a0L3Y3494a?dl=0)

- [additional utils](https://www.dropbox.com/sh/bi6c0rs96jo5oom/AAACBeOgHUkEUsjxtJnz-MkVa?dl=0)
