# SDG dataset

This is a collecition of notebooks working withthe data set available on [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/).

- [country_diaggregation](https://github.com/felix-laumann/SDG-dataset/blob/master/country_diaggregation.ipynb) splits data in separate `csv` files per country, and all other groupings. For all other information, including where to download the original data set, see the notebook. The separate `csv` files can also directly be downloaded [here](https://www.dropbox.com/sh/z54b8kgb7awpk56/AADGRnBd3ZH7unFwC9PnB8xaa?dl=0).

- [imputations](https://github.com/felix-laumann/SDG-dataset/blob/master/imputations.ipynb) imputes missing values in the data set either with a **weighted k nearest neighbour (w-kNN)** algorithm, if less than 9 measurements are available from the years 2000 to 2018, or with **Gaussian processes (GPs)**, if more than 9 measurements are available.

- [similarities](https://github.com/felix-laumann/SDG-dataset/blob/master/similarities.ipynb) computes the [distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between each unique pair of sub-indicators in all groupings.
