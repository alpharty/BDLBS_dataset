# DBLBS_dataset


## Composition

This subset describes 1000 patients subjected to inguinal hernia operation under laparoscopy.

The observations are made every 30 seconds.

The set have two sections :

- Univariate: each file is specific to a variable and contains the 1000 time series for this variable
- Multivariate: each patient is described through two files, one for the event trace, and one for the multivariate time series.

In the Multivariate section, each anaesthetic profile n°X is composed of 2 files :

- X_events.txt, for the events
- X_series.txt, for the multivariate time series

All files use comma as separator.
