# pident2
Source code for "Using attention neural networks to estimate individual-level pig growth trajectories from group-level weight time series".

Packages used:
- Python 3.8.16
- Pytorch 1.13.1
- Cuda 11.7.1
- Captum 0.6.0
- Numpy 1.22.3
- Scipy 1.7.3
- Scikit-learn 1.1.1
- Matplotlib 3.2.2

Script list:
- train.py - To train a new model.
- metrics.py - To evaluate a model's predictive performance. Also used to generate the necessary files for growth forecasting with the "--index" option.
- forecast.py - To use predicted growth trajectories in a downstream growth forecasting task.
- interpret.py - To interpret predictions made by a model.
