# DBLBS_dataset


## Composition

This dataset is composed of 4 subsets. Each subset is composed of 1000 traces and differ in the time between time series values : [30,60,90,120] second.

Each set have two sections :
- Univariate, each file is specific to a variable and contain the 1000 time series for this variables
- Multivariate, each pair of file is specific to a patient and contain event or time series.

In the multivariate section, each trace n°X is composed of 2 files :
- X_events.txt, for the events
- X_series.txt, for the multivariate time series

All files use comma as separator for datas.
