**logistic growth analysis**

*Question 1.*

These analyses used the "experiment1.csv" file provided. A linear model applied to the pre-plateau phase (t < 2500) as apparent from the graphical plot gives a slope coefficient of 0.0080570 and intercept of 8.2606961.
These estimates can be considered fairly accurate, the standard error of each being an order of magnitude smaller than the value itself, and an adjusted R squared of 0.9562 indicates very good model fit.

Applying a linear model to the post-plateau phase (t > 2500) on the non-log-transformed dataset gives an intercept estimate of 5.979x10^10. 
This in turn estimates the parameter K from the model of logistic growth. A high t value of 551.4 and the clear correspondence with the plateau y level on the plots indicate very good fit.

When plotted as an exponential function against the data these linear-derived N0, r and K estimates produce a function that resembles the best fit of the curve 
in shape but is shifted in the positive x (t) direction by around t=1000. 
This is clearly capturing a correct dynamic but the function is sensitive to small errors and this shift means that the derived function 
poorly predicts the data even if linear functions of its parameters do so better (up to y~k).

*Question 2.* The estimated parameters N0 and r of the logistic equation are inserted into an exponential equation N= N0exp(rt) and when t=4980, N, the population size = 2.200836x10^18.
In comparison, for t=4980 under the logistic model of growth with these parameters, N= 5.979x10^10, 8 orders of magnitude smaller.
t=4980 sits in the region of this logistic function where N is almost equal to K and the population growth rate is essentially 0, the stationary phase.

*Question 3.* Red line shows exponential model and blue line indicates logistic model.


![image](https://github.com/solarproblems/logistic_growth/assets/152936548/27cd23cd-e136-4d28-b87f-55afa72753bf)



