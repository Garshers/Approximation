# Function Approximation Exercises

This repository contains a set of exercises focused on approximating functions over specified intervals using various polynomial methods. The goal is to approximate given functions and analyze the accuracy of the approximations using Legendre polynomials, point approximations, and sine series approximations.

## Exercises Overview

### Exercise 1: Quadratic Approximation using Legendre Polynomials

In this exercise, a function defined on the interval [-1, 1] is approximated using Legendre polynomials up to degree N=2.

- **Objective**: Approximate the given function using Legendre polynomials and compute the approximation error.
- **Functionality**: The code computes the coefficients for the Legendre polynomials (P0, P1, P2) and uses them to approximate the function. The error is calculated as the squared difference between the original and the approximated functions.

### Exercise 2: Polynomial Approximation Using 6 Points and a 3rd Degree Polynomial

This exercise approximates a function over the interval [0, π] using point approximation with 6 points and a third-degree polynomial.

- **Objective**: Approximate the function using polynomial interpolation and analyze the error.
- **Functionality**: The code builds a system of equations using the sampled points and computes the coefficients for the polynomial approximation. The approximation error is calculated as the average absolute difference between the original and the approximated function.

### Exercise 3: Polynomial Approximation for Different Degrees (1 to 4)

This exercise approximates a function over the interval [0, π] using point approximation with 6 points and varying degrees of polynomials (from degree 1 to 4).

- **Objective**: Compare the accuracy of polynomial approximations for degrees 1 through 4.
- **Functionality**: The code generates approximations for polynomials of different degrees and calculates the approximation errors. The results are plotted, and the errors for each polynomial degree are reported.

## Error Analysis

For each exercise, the approximation error is computed as the average absolute difference between the original function and the polynomial approximation at sampled points. This error metric helps evaluate how well the polynomial approximation performs for different degrees.

## Functions and Usage

The repository provides functions to perform the approximations and error analysis for each exercise. Here's a breakdown of the main functions:

1. **Legendre Polynomial Approximation**: Approximates the function using Legendre polynomials and calculates the approximation error over the interval.
2. **Point Approximation**: Uses point-based polynomial approximation (with sampled points) to approximate the function and computes the error.
3. **Sine Series Approximation**: Approximates the function using a sine series and calculates the approximation error for varying degrees of the series.

Each function outputs the approximation error, plots the original and approximated functions, and provides a breakdown of the polynomial coefficients.

## Example Usage

For each exercise, the script will:
- Approximate the function using the specified method (e.g., Legendre polynomials, point approximation).
- Compute and display the approximation error.
- Plot the original function alongside the approximation to visually compare the results.

## Conclusion

This repository provides tools for approximating functions using various polynomial methods, allowing you to analyze the accuracy of different polynomial approximations. It is designed to help users understand polynomial approximation methods and how their accuracy changes with the degree of the polynomial.

By running the exercises, users can gain insights into the behavior of polynomial approximations and their performance on different types of functions.

## Requirements

- A MATLAB environment or equivalent software capable of running MATLAB code.

## License

This project is open-source and licensed under the MIT License.
"# Approximation" 
