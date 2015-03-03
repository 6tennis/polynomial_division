# Polynomial Division
This program divides polynomials by plugging coefficients into a formula. 
# The Formula
For a fifth-degree polynomial, the formula is:
(a5/b1)*x^4 + (1/b1)*((a4 − (b0/b1)*a5)*x^3 + (1/b1)*[a3 − (b0/b1)*(a4 − (b0/b1)*a5)]*x^2 + (1/b1)*{a2 − (b0/b1)*[a3 − (b0/b1)*(a4 − (b0/b1)*a5)]}*x + (1/b1)*(a1 − (b0/b1)*[a2 − (b0/b1)*{a3 − (b0/b1)*(a4 − (b0/b1)*a5)}]) + R
R is the remainder of the quotient, and it is equal to:
[a0 − (b0/b1)*(a1 − (b0/b1)*{a2 − (b0/b1)*[a3 − (b0/b1)*(a4 − (b0/b1)*a5)]})]
This can be a bit confusing to grasp at first, but you may realize that the formula is repetitive. It will work with any degree polynomial dividend. So, we can write a program to solve this formula by using an array. We define the size of the array based on the degree of the polynomial dividend, and we use those arrays to do the necessary calculations.
# System Requirements
To run this program, you need JDK 8.
