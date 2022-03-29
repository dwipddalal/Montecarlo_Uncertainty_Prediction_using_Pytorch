# Montecarlo Uncertainty Prediction
## Introduction
Monte Carlo is a term used in statistics to describe a group of computational techniques that use repeated random sampling to derive a distribution of a numerical quantity.

Gal & Ghahramani (2016) introduced Monte Carlo Dropout as a brilliant discovery that regular dropout may be read as a Bayesian approximation of a well-known probabilistic model: the Gaussian process. The various networks (with various neurons removed) can be viewed as Monte Carlo samples from the space of all available models. This gives us a mathematical foundation on which to reason about the model's uncertainty, and it turns out that it often enhances its performance.

## Results 
It is evident from the code that on applying Montecarlo drop-out the model becomes more uncertain about it's predictions. Also on stacking the multiple models with montecarlo drop-out layer it is observed that the overall accuracy of the model's prediction increases. 
