#Bessel Functions

## Description
This Python project explores numerical methods in physics through two main components:

### 1. Numerical Bessel Function Calculation
- Calculates $\( J_m(x) \)$, the Bessel function of the first kind, using the trapezium rule.
- Approximates the integral:
  
   $\[
  J_m(x) = \frac{1}{\pi} \int_0^\pi \cos(m\theta - x \sin\theta) \, d\theta
  \]$

  with 10,000 subintervals for high accuracy.
- Generates plots for \( J_0(x) \), \( J_1(x) \), and \( J_2(x) \) over the range \( 0 \leq x \leq 20 \).

### 2. Diffraction Pattern of a Circular Lens
- Uses \( J_1(x) \) to calculate the relative intensity of light through a circular aperture.
- Computes the diffraction pattern using:
  \[
  \frac{I(r)}{I_0} = \left( \frac{2 J_1(x)}{x} \right)^2, \quad x = \frac{\pi r}{10 \lambda}, \quad \lambda = 600\,\text{nm}
  \]
- Produces a plot showing the central bright spot and concentric rings decreasing in intensity.

## Libraries
- NumPy
- Matplotlib

## Files Included
- Python script implementing numerical integration and plotting
- Figures showing Bessel function plots and diffraction patterns

## Purpose
Demonstrates the application of numerical methods to solve physics problems and visualize optical diffraction patterns.
