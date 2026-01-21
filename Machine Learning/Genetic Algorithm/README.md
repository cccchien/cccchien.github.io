# Genetic Algorithm solving non-linear regression
## Problem
Find the best 6 parameters for LPPL formula that minimize sum of absolute distance

Assumption: $t_c$ occurs at the last day of the data we obtained

LPPL formula: 

$$
\ln \left(p(t)\right) \approx A + B (t_c - t)^\beta\left[ 1 + C \cos\left(\omega\ln\left(t_c-t\right)+\phi\right)\right]
$$

with restriction of

- $A>0$ 
- $B<0$   
- $C\neq 0$  
- $0<\beta<1$ 
- $0<\phi<2\pi$
- $t_c$ is the time of bubble

## Initial Setup

- p = 10000 , standing for population
- r = 0.02 , standing for survival rate for each evolution
- m = 500 , standing for genes that mutated for each evolution
- generation = 15 , standing for generations evolved

## Results

### Parameters and Minimum SAD

<img width="700" height="300" alt="image" src="https://github.com/user-attachments/assets/e832732d-261c-40b1-aaf9-921d2eb6c035" />

### Plots

<img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/e0770008-7207-4a77-a05d-3ab42fd2d4c6" />



