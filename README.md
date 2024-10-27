# casadi-presentation
A CasADi's introduction using Jupyter Lab \
www.casadi.org


This repository contains my presentation of CasADi's capabilities. Inside you can find 3 Jupyter notebooks:

-**CasADi.ipynb**  
  - Containing an introduction to CasADi as a mathematical modeling tool.
    
-**Parametric Estimation.ipynb**
  - It contains a parametric estimation implementation. This notebook reproduces Bock's article, which introduces multiple shootings. (*Recent Progress in the Development of Algorithms and Software for Large Scale Parameter Estimation Problems in Chemical Reaction Systems - Bock, Schlöder, 1986*)


Installation & run:
```
git clone git@github.com:nashmit/casadi-presentation.git
conda create --name <environment_name> --file requirements.txt
conda activate <environment_name>
jupyter-lab
```

