# WIWB_examples
## Overview
Examples of how to query data from the WIWB using python and examples of how machine learning algorithms could be applied to that data.

## Contents
The `query_examples.ipynb` notebook contains examples of queries to the various datasources in the WIWB.

The `usage_examples.ipynb` contains examples of how machine learning algorithms can be applied to data from the WIWB. It includes an example of univariate timeseries forecasting using Facebooks Prophet model. As wel as two examples of anomaly detection using the IsolationForest model. 

### Notes
#### Credentials
Credentials are needed to query the WIWB api, you'll need to supply your own to get the necessary data. fill in the username and password in the notebooks at authentication section.

#### Environment
A anaconda environment file is supplied that can be used to install the necessary packages. If anaconda is installed you can install the environment with `conda env create -f environment.yml`.
