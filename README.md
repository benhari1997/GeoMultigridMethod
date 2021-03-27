# Geometric Multigrid solver implementation
___

The aim of this notebook is to try to solve some specific partial equations in 1 and 2 dimension, starting from the Poisson equation on a 1D space and ending with ana anistropic one on a 2D space.
The provided notebook is devided into various subsections as follows:
### 1. Problem modelisation :
#### i. discretisation (Finite difference method):
- 1D Poisson's Equation : ($-\Delta u(x) = f(x) $)
- 2D isotropic Equation : $(-\Delta u(x,y) +\gamma u(x,y) = f(x,y))$
- 2D anistropic Equation : $(-du(x,y)/dx² -\epsilon  du(x,y)/dy² = f(x,y))$
#### ii. Laplacians construction (1D, 2D and 2D anistropic).
### 2. Linear solvers implementation :
- Jacobi Over Relaxation (JOR).
- Successive Over Relaxation (SOR).
### 3. Multigrid method implementation :
- Projection/Restriction matrix implementation (I).
- V-Cycle multigrid implementation.
- W-Cycle multigrid implementation.
### 4. Results :
- Plotting the different solvers results.
- Analysis and comparison over different values of some parameters.

For more details please check the notebook.
___
___
> Author : Benhari Abdessalam

> Date 17/01/2021