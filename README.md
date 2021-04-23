## Setup - Dataset - Installation Dependencies
Either download the .csv from this github repo or from the UCI Machine Learning Repository, [Combined Cycle Power Plant Data Set](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant). Afterwards you can load the notebook in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/notebooks/colab-github-demo.ipynb)

You can see the results of the analysis here, [electrical_energy_output_ann_regression.ipynb](electrical_energy_output_ann_regression.ipynb) . If the notebook isn't already loaded from GitHub, please refresh/reload.

## Electrical Energy Output prediction using ANN Regression
The aim of this notebook is to create a data model that predicts the net hourly electrical energy output (EP) of the Combined Cycle Power Plant using available hourly average ambient variables.

### More about Combined-Cycle Power Plants
A combined-cycle power plant is an electrical power plant in which a Gas Turbine (GT) and a Steam Turbine (ST) are used in combination to produce more electrical energy from the same fuel than that would be possible from a single cycle power plant.

The gas turbine compresses air and mixes it with a fuel heated to a very high temperature. The hot air-fuel mixture moves through the blades, making them spin. The fast-spinning gas turbine drives a generator to generate electricity. The exhaust (waste) heat escaped through the exhaust stack of the gas turbine is utilized by a Heat Recovery Steam Generator (HSRG) system to produce steam that spins a steam turbine. This steam turbine drives a generator to produce additional electricity. CCCP is assumed to produce 50% more energy than a single power plant.

## MIT License

Copyright (c) 2021 Efstratios Marinos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
