# adaptiveBehavior
Age classes stratified by risk and adaptive behavior during epidemics

Source code for Age classes stratified by risk and adaptive behavior during epidemics, for Ronan F. Arthur, May Levin, Alexandre Labrogere, Marcus W. Feldman (2023).

Preprint available on bioRxiv.

This repository includes Python source code and Jupyter notebooks including:

1. **Equilibrium_2Populations**: This Jupyter notebook contains the Python source code that builds a computational dynamic model for a two-population scenario. The model iteratively solves the system of dynamic equations, representing the behavior of age classes stratified by risk during an epidemic. The dynamics are then visualized for the parameter sets defined in the paper.

2. **Equilibrium_3Populations**: This notebook extends the previous model to a three-population scenario. This allows for more complex interactions and behaviors to be modeled and understood. As with the two-population model, the resulting dynamics are visualized for the paper's parameter sets.

3. **FrequencyPlots_dynamics**: This notebook generates frequency plots that map out the periodic behavior of the system under varying `a21` and `a22` values. The categorization of different levels into periodicity functions is then graphed onto a heat maps in order to provide insights into the underlying dynamics of the system.

4. **BifurcationGraphs_dynamics**: In this notebook, bifurcation diagrams are created to show the possible states of the dynamic system as a function of a bifurcation parameter (b0 or c12). 
