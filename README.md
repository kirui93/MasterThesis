### Description

This folder contains all the codes that I used in my master thesis.

It contains two R-markdown files and a Python file. The R-markdown files being implemented in R-studio and the Python file being implemented in Jupyter notebook.

The Rmarkdown files are for implementation of the Markowitz model with and without risk-free asset and Integrated management formulation model with and without a risk-free asset. 

The theory of the Markowitz model doesn't need any specific package for its implementation and so we can find all the concepts for the Markowitz model in R by just using the theory itself.

For the Integrated Management Formulation model, this is a linear model and so we use the already developed package called "linprog" in R which is suitable for handling linear problems. In this package, we use the function called "solveLP" for solving linear programs(https://www.rdocumentation.org/packages/linprog/versions/0.9-2/topics/solveLP).

The Jupyter notebook is for implementation of the Entropic Value-at-Risk based model. The Entropic Value-at-Risk model is a non-linear optimization problem depending on more than one variable. The choice to use Python for this model is because there are nice packages in Python to handle non-linear optimization problems which depend on more than one variables. Such packeges include "scipy.optimize.minimize"  as in the following site (https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.minimize.html). This package is good for our optimization purposes since we want to minimze the EV@R and so the programming suits our objective.

The results and discussions of the models are asmcontained in Chapter 6 of the thesis. Not all the results from the models are discussed but the most important results in the thesis are included. 



