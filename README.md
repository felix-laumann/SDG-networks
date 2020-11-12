# SDG climate change networks

We retrieve SDG data from the [World Bank](http://datatopics.worldbank.org/sdgs/) for all SDGs except SDG 13 which we take from the [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/). Annual average temperatures on a country-level are taken from the [CRU data set](https://crudata.uea.ac.uk/cru/data/hrg/cru_ts_4.04/crucy.2004161557.v4.04/countries/tmp/). The 17 SDGs and climate change, measured by annual average temperature, are seen as 18 variables which want to be analysed on their inter-dependencies, often referred to as *interlinkages*.
We compute the [partial distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between any two variables given any subset of the remaining variables.


## Notebooks

- [1_Temperature](https://github.com/felix-laumann/SDG-dataset/blob/master/1_Temperature.ipynb) prepares the CRU data set to be appended to the SDG indicators. 

- [1_data_preparation](https://github.com/felix-laumann/SDG-dataset/blob/master/1_data_preparation.ipynb) splits data in separate `csv` files per country, appends the temperature, and standardises the data. 

- [2_imputations_concatenating](https://github.com/felix-laumann/SDG-dataset/blob/master/2_imputations_concatenating.ipynb) imputes missing values in the data set with a **weighted k nearest neighbour (w-kNN)** algorithm, and averages and concatenates data to target and goal-level.

- [3_distance_cor_continents](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor_continents.ipynb) and [3_distance_cor_groups](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor_groups.ipynb) computes the partial distance correlation between each unique pair of two variables given any subset of the remaining variables for continents and groups, respectively. These notebooks include the visualisations of the networks and eigenvector centrality figures.

- [5_Additions](https://github.com/felix-laumann/SDG-networks/blob/master/5_Additions.ipynb) includes the visual exploration of dependencies.
