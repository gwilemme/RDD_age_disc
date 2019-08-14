*** This repository is incomplete. IN PROGRESS ***

# RDD_age_disc
Online appendix of the project
'Age discontinuity and nonemployment benefit policy evaluation through the lens of job search theory'
by Bruno Decreuse and Guillaume Wilemme.

### Structure of the repository
This repository contains the Julia code used to simulate the 4 models. The code is written with Jupyter notebooks.
The code runs with Julia 1.1.

The folder `code` contains the Jupyter notebooks. GitHub can directly display these notebooks.
Sometimes GitHub does not manage to display a notebook. 
You can either download the html records of the notebook within the folder `html`, and open them with your browser.
Alternatively you can use the viewer https://nbviewer.jupyter.org/.

### Structure of the code
`core_fun.ipynb` is the notebook containing the main routines for the four cases: Quebec, France, Austria, Germany. 
The code is commented with the equations of the model.
`core_fun.ipynb` is called with the `NBInclude` package in each of the four cases studied.

For each case, there are two notebooks. `simu_XXX_benchmark` computes the model parameters, graphs and regression coefficients used in the paper.
The robustsness tables that appear in the appendix are obtained with `simu_XXX_robust`.

