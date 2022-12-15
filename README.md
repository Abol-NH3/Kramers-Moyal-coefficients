# Kramers-Moyal-coefficients

Here we try to estimate the Kramers-Moyal-coefficients of a given data set.\
we have:
```math
K^{(l)}(x,t,tao)=<(x(t+tao)-x(t))^l|x(t)>
```
We use binning method to estimate $K^{(l)}(x,t,tao)$ for x

This method requires a good amount a data to give ...  results.

The higher $K^{(l)}$ you want to get, the more data points you are going to need

there is also a Kernel And a moment-based method which are also in my GitHub

the code calculates $K^{(l)}$ for $l=1,2,4,6$ which are the most commonly used Kramers-Moyal-coefficients\
but you can add your other preferred l easily by just adding a few lines to the code
