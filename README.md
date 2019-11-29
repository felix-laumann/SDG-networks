# SDG dataset

This is a collecition of notebooks working with the data set available on [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/). 

If you had asked yourself whether working with data provided by the [World Bank](http://datatopics.worldbank.org/sdgs/) would be better, please be aware that indicators are not always the same. This [table](https://www.dropbox.com/s/xbqldi07709wsvk/indicator_table.ods?dl=0) compares both sets of indicators.

## Notebooks

- [1_data_preparation](https://github.com/felix-laumann/SDG-dataset/blob/master/1_data_preparation.ipynb) splits data in separate `csv` files per country, and all other groupings. For all other information, including where to download the original data set, see the notebook. 

- [2_imputations_concatenating](https://github.com/felix-laumann/SDG-dataset/blob/master/2_imputations_concatenating.ipynb) imputes missing values in the data set with a **weighted k nearest neighbour (w-kNN)** algorithm.

- [3_distance_cor](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor.ipynb) computes the [distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between each unique pair of indicators, targets, and goals in all countries and continents.


## Direct downloads

- [original `csv` files](https://www.dropbox.com/sh/z54b8kgb7awpk56/AADGRnBd3ZH7unFwC9PnB8xaa?dl=0)

- [standardised `csv` files](https://www.dropbox.com/sh/5jiz4ytf7gzbdjy/AACOcMx5SE-xFmq5AZSOjIuma?dl=0)

- [standardised `csv` files with imputations](https://www.dropbox.com/sh/fgwpxet2heuf9gd/AACshLajFaBDb13a0L3Y3494a?dl=0)

- [additional utils](https://www.dropbox.com/sh/bi6c0rs96jo5oom/AAACBeOgHUkEUsjxtJnz-MkVa?dl=0)
