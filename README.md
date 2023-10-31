The first jupyter notebook dealt with the learning and implementing of the ARIMA model

next we need to focus on how to tune the p, d, q values for the model
(we're gonna use the same dataset - using the grid method, ie going through all the options we found one ans, need to compare now)
(and also compare btw the 2 methods - auto and plots)
follow this link - https://blog.devgenius.io/finding-optimal-p-d-and-q-values-for-your-arima-model-94669a909a35

there are 2 main ways:
a. Using Plots
b. Using Auto-ARIMA

a.

Using plots like PACF (Partial Autocorrelation function) & ACF (Autocorrelation function) for P and Q respectively

P — To find the best P value for any PACF plot

I've put the rest of the documentation in the tuning juptyer notebook

note:

BOTH RESULTS TURNED OUT TO BE SAME
