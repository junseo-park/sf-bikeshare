# SF Bikeshare

This project aims to explore bikeshare data from the Ford GoBike program across five cities in the San Francisco Bay Area. With the meteoric rise of bikeshare/scootershare services across the world, it was an interesting journey to revisit what kind of ridership patterns we could extract from bikeshare data. Following EDA, I also attempted to create a model that could predict ridership based on features extracted from the data; alas, the two years of data that we had is seemingly insufficient to create a robust model that does not overfit to the training set (not to mention, challenges in fitting to a time series dataset).

## Writeup
--TBD!--

## Data
Data were collected from [Kaggle](https://www.kaggle.com/benhamner/sf-bay-area-bike-share); some data files (i.e. `database.sqlite`, `status.csv`) have been omitted from this repository because they were not used in the analysis, and they are too large to upload to GitHub.

## Analysis
Notebooks containing analysis can be found in [notebooks](./notebooks), and data (raw and cleaned) can be found in [data](./data)

## Reproduction
This project can be reproduced by creating a Python3 virtualenv with the dependencies listed in [`requirements.txt`](./requirements.txt)

## References
- [https://towardsdatascience.com/time-series-nested-cross-validation-76adba623eb9](https://towardsdatascience.com/time-series-nested-cross-validation-76adba623eb9)
