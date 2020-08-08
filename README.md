# SDG notebooks

This is a collecition of notebooks working with data sets available on [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/) and [World Bank](http://datatopics.worldbank.org/sdgs/). 


## Notebooks

- [1_Temperature](https://github.com/felix-laumann/SDG-dataset/blob/master/1_Temperature.ipynb) prepares the [CRU dataset](https://crudata.uea.ac.uk/cru/data/hrg/cru_ts_4.04/crucy.2004161557.v4.04/countries/tmp/) to be appended to the SDG indicators. 

- [1_data_preparation](https://github.com/felix-laumann/SDG-dataset/blob/master/1_data_preparation.ipynb) splits data in separate `csv` files per country, appends the temperature, and standardises the data. 

- [2_imputations_concatenating](https://github.com/felix-laumann/SDG-dataset/blob/master/2_imputations_concatenating.ipynb) imputes missing values in the data set with a **weighted k nearest neighbour (w-kNN)** algorithm, and averages and concatenates data to target and goal-level.

- [3_distance_cor_continents](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor_continents.ipynb) and [3_distance_cor_groups](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor_groups.ipynb) computes the [partial distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between each unique pair of two goals given *any subset of the remaining goals* for continents and groups, respectively. This notebook includes visualisations of SDG networks.
