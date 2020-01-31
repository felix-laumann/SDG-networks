# SDG datasets

This is a collecition of notebooks working with data sets available on [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/) and [World Bank](http://datatopics.worldbank.org/sdgs/). 


## Notebooks

- [1_data_preparation](https://github.com/felix-laumann/SDG-dataset/blob/master/1_data_preparation.ipynb) splits data in separate `csv` files per country and other groupings. For all other information, including where to download the original data set, please see the notebook. 

- [2_imputations_concatenating](https://github.com/felix-laumann/SDG-dataset/blob/master/2_imputations_concatenating.ipynb) imputes missing values in the data sets with a **weighted k nearest neighbour (w-kNN)** algorithm and concatenates data to target and goal-level.

- [3_distance_cor](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor.ipynb) computes the [partial distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between each unique pair of targets and goals for continents and groups (**includes visualisations of SDG networks**).

- [4_Granger-causality](https://github.com/felix-laumann/SDG-dataset/blob/master/4_Granger-causality.ipynb) computes the Granger-like cause-effect relationships between goals for a maximum lag of three years.
