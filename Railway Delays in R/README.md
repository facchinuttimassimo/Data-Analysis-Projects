Railway Delay Analysis – Bologna to Milan

An exploratory and predictive analysis of train delays on the Bologna–Milan route, one of Italy's busiest intercity corridors, using operational data from Trenitalia (December 2017 – March 2018).


Overview

This project investigates the temporal and spatial patterns of train delays on the Bologna–Milan line, and builds a predictive model to estimate the probability of a significant delay (> 5 minutes).

The analysis covers:


Exploratory analysis — delay distributions, patterns by station, month, and day of the week
Linear regression — modelling delay magnitude as a function of temporal variables
Logistic regression — predicting the probability of a significant delay, with ROSE resampling to address class imbalance



Key Findings


The delay distribution is strongly right-skewed: the median delay is 2 minutes, while the mean is 4.3 minutes, driven upward by a minority of trains with substantial delays.
March is the worst month by a wide margin (average > 7 min), likely due to strikes or adverse weather.
Wednesday is the most delayed weekday; Sunday consistently shows the lowest delays (~3 min average).
Later departures are associated with slightly higher delays, consistent with schedule propagation effects throughout the day.
The logistic regression achieves an AUC of 0.594 — limited but non-trivial predictive power given the absence of external variables (weather, strikes, mechanical failures).
