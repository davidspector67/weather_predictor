# Deep Learning Based Weather Prediction Architecture Comparison

This repository contains a comparative look at LSTM and multi-layer feed-forward neural network architectures regarding
the time series forecasting task of predicting future weather given past weather data.

Before running and viewing our [reproduceable results](comparison_results.ipynb), our [Conda](https://docs.anaconda.com/free/miniconda/miniconda-install/) Python environment must be created to run the notebook in for best results.

## Environment Setup

To construct a Conda Python environment to run this pipeline with, ensure Conda is installed and run

``` shell
conda env create -f env.yml
```

To run this environment, run the command

```shell
conda activate weather_predict
```

Note that this environment must be connected to `comparison_results.ipynb` before running. For help achieving this, see [this article](https://saturncloud.io/blog/how-to-use-conda-environment-in-a-jupyter-notebook/).

Also note that this environment was only tested on OSX, so compatability issues may exist on other operating systems.
