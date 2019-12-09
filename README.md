# SDG dataset

This is a collecition of notebooks working with the data set available on [UN Statistics Division](https://unstats.un.org/sdgs/indicators/database/). 

If you had asked yourself whether working with data provided by the [World Bank](http://datatopics.worldbank.org/sdgs/) would be better, please be aware that indicators are not always the same. This [table](https://www.dropbox.com/s/xbqldi07709wsvk/indicator_table.ods?dl=0) compares both sets of indicators.

## Notebooks

- [1_data_preparation](https://github.com/felix-laumann/SDG-dataset/blob/master/1_data_preparation.ipynb) splits data in separate `csv` files per country, and all other groupings. For all other information, including where to download the original data set, see the notebook. 

- [2_imputations_concatenating](https://github.com/felix-laumann/SDG-dataset/blob/master/2_imputations_concatenating.ipynb) imputes missing values in the data set with a **weighted k nearest neighbour (w-kNN)** algorithm and concatenates data to target and goal-level.

- [3_distance_cor](https://github.com/felix-laumann/SDG-dataset/blob/master/3_distance_cor.ipynb) computes the [distance correlations](https://projecteuclid.org/euclid.aos/1201012979) between each unique pair of indicators, targets, and goals in all continents.

- [4_distance_visualisation]() visualises the conditional distance correlations as networks.

- [5_Granger-causality](https://github.com/felix-laumann/SDG-dataset/blob/master/5_Granger-causality.ipynb) computes the Granger-like cause-effect relationships between goals for a maximum lag of three years.


## Direct downloads

- [original `csv` files](https://www.dropbox.com/sh/x13mq39n4tod4fe/AADBq7gIx6eMk1m2Ru_lodXIa?dl=0)

- [standardised `csv` files](https://www.dropbox.com/sh/p8k6gprs53ilprp/AACng120qDQYbQUCrdjbezsea?dl=0)

- [standardised `csv` files with imputations](https://www.dropbox.com/sh/3lx4o5rbuq6ffv1/AABt0ZDgZ4CXDL2rQgE3hHLda?dl=0)

- [and everything else](https://www.dropbox.com/sh/cxnm0sar6yfg6mq/AACDUMEVLj6u62IgfkBTuee7a?dl=0)
