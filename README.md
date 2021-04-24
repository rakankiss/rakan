# In this project we will learn how to solve switching equations using Matlab code
this is matlab code for Permutation 
first run the matlab code 
then you should input the value of n and input the value of r 
so the matlab output is the answar of equation 
the code of matlab 
% Script to calculate permutations of n items taken r at at time.
% That is, matlab code to calculate P(n,r)
n = input('Enter n ');
r = input('Enter r ');
P = factorial(n)/factorial(n-r) %Using the formula P(n,r)= n!/(n-r)! and the factorial function of matlab.
fprintf('The value of P(%d,%d) is: ',n,r);
disp(P)
