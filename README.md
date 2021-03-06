# PuLP application to the FSGSP

This repo shows the optimisation of the flowshop group scheduling problem (FSGSP) using the PuLP module and IBM's ILOG CPLEX 12.0 solver in Python 3.8.

The repo contains the following files:

* [A mathematical formulation for the FSGSP](https://github.com/scaceres21/pulp_application_fsgsp/blob/main/Mixed-Integer%20Programming%20Model%20for%20the%20FSGSP.ipynb): The Mixed-Integer Programming Model 1 presented by Naderi and Salmasi (2012). This model was proposed to minimise the Total Completion Times of Jobs.

* [A Jupyter notebook with the formulation of the problem in PuLP](https://github.com/scaceres21/pulp_application_fsgsp/blob/main/PuLP%20formulation%20for%20the%20FSGSP.ipynb): This notebook contains the function defined for the formulation of the flowshop group scheduling problem in PuLP. The notebook also contains a randomly generated example.
