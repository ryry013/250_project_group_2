To-do list (sign in with UC Davis email):
https://docs.google.com/document/d/1COlHCDnNZxSyn41l6iGPOnaCOLIA3HwKIXGB5Oj28jA/edit

Project directory is as follows:

```
250_project_group_2/  
├── debugging_testing/  
│   └── ... = various jupyter notebooks used to test or debug elements of the project  
├── notebooks/  
│   └── plotting.ipynb - the notebook to run, show, and describe our Markov chain  
├── results/  
│   └── omega_contour_plot.pdf - the final result contour plot image  
├── source/  
│   ├── cosmo_model.py - an implementation of a cosmological model to calculate distance modulus  
│   └── mcmc.py - the main code to run a MCMC algorithm   
└── unittests/  
    ├── test_likelihood_map.py - makes 1D likelihood maps to see if there are peaks in expected places  
    └── test_compare_cosmomodel_vs_astropy.py - walks over test parameters and compares output of our model vs astropy  
```