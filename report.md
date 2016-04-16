UECM3033 Assignment #3 Report
========================================================

- Prepared by: E Hung Yang
- Tutorial Group: T3

--------------------------------------------------------

## Task 1 --  Gauss-Legendre formula

The reports, codes and supporting documents are to be uploaded to Github at: 

https://github.com/EHungYang1/UECM3033_assign3

Explain how you implement your `task1.py` here.
The function of def gausslegendre(f,a,b,n=20) is put in to find the Gauss-Legendre quadrature. And also the polynomial.legendre.leggauss is used to find the sample points and weights for Gauss-Legendre quadrature. I used Lagrange polynomial to tranfrom the interval which is given by y = a((x-1)/(-1-1)) + b((x+1)/(1+1)) and the jacobian for this transformation is (b-a)/2.

Explain how you get the weights and nodes used in the Gauss-Legendre quadrature.
Weights and nodes can be used by putting in np.polynomial.legendre.leggauss.
---------------------------------------------------------

## Task 2 -- Predator-prey model

Explain how you implement your `task2.py` here, especially how to use `odeint`.


Put your graphs here and explain.

Is the system of ODE sensitive to initial condition? Explain.

-----------------------------------

<sup>last modified: change your date here</sup>
