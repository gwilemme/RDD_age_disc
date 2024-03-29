# RDD_age_disc
Online appendix of the project
'Age discontinuity and nonemployment benefit policy evaluation through the lens of job search theory'
by [Bruno Decreuse](https://sites.google.com/site/brunodecreuseecon/) (Aix-Marseille Univ.) and [Guillaume Wilemme](http://www.gwilemme.com/) (Univ. of Leicester).

### Structure of the repository
This repository contains the Julia code used to simulate the 4 models. The code is written with Jupyter notebooks.
The code runs with Julia 1.1.

The folder `code` contains the Jupyter notebooks. GitHub can directly display these notebooks.
Sometimes GitHub does not manage to display a notebook. 
We suggest using the url on GitHub with the viewer https://nbviewer.jupyter.org/.

### Structure of the code
`core_fun.ipynb` is the notebook containing the main routines for the four cases: Quebec, France, Austria, Germany. 
The code is commented with the equations of the model.
`core_fun.ipynb` is called with the `NBInclude` package in each of the four cases studied.

For each case, there are two notebooks. `simu_XXX_benchmark` computes the model parameters, graphs and regression coefficients used in the paper.
The robustsness tables that appear in the appendix are obtained with `simu_XXX_robust`.

### Running codes
To run the codes, download the notebooks in the same file. Simulations for Quebec and France are relatively fast. They can be run on your own PC or laptop.
Simulations for Austria and Germany are more demanding. We recommend using a server. It would then take less than a day to run a notebook.
