# -Learning-to-Solve-Computational-Fluid-Dynamics-CFD-Equations-using-Fourier-Neural-Operator

This project demonstrates how Machine Learning can learn to solve Computational Fluid Dynamics (CFD) equations — specifically, the 2D Poisson equation — using Fourier Neural Operators (FNOs).

Instead of relying on traditional numerical solvers (like finite-difference or finite-volume methods), the model learns the underlying mapping (operator) between the source term 
𝑓
(
𝑥
,
𝑦
)
f(x,y) and the solution field 
𝑢
(
𝑥
,
𝑦
)
u(x,y) directly from data.


−∇
2
u(x,y)=f(x,y)

The goal is to explore how deep learning can approximate partial differential equation (PDE) solvers and accelerate CFD simulations.
