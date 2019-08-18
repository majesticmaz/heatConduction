# 1D Heat Conduction Solver
A 1D heat conduction solver using Finite Difference Method and implicit backward Euler time scheme.  

## Features:  
    1. Finite Difference Method.  
    2. Centered Differecing in space (second order accuracy), implicit backward Euler time scheme (First order accuracy).  
    3. Using Newton's method to solve discretized equation system at each time step.  
    4. Two types of boundary conditions, fixed temperature and fixed heat flux.  
    5. Current version only support constant material properties, will be upgraded.  
    6. Incoporate with postprocessing module and analytic solution comparison.   

## How to run:  
    1. In any Python IDE, open parameter.py, execute.  
    2. To compare with analytic solution, open analyticSolution.py, execute.  
    
## Reference:
If you are using the code for your research or study, please consider cite me!
1. Thermomechanical Coupling for Charring Ablators [Link](https://doi.org/10.2514/1.T5194).
2. Thermal Expansion for Charring Ablative Materials [Link](https://doi.org/10.2514/1.T5718).
