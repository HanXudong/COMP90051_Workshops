# COMP90051_Workshops

## L2 Nrom /  Shrinkage Methods

https://web.stanford.edu/~hastie/Papers/ESLII.pdf
The Elements ofStatistical Learning

page 64

In addition, notice that the intercept $\beta_0$ has been left out of the penalty term. Penalization of the intercept would make the procedure depend on the origin chosen for Y; that is, adding a constant $c$ to each of the targets $y_i$ would not simply result in a shift of the predictions by the same amount $c$. It can be shown (Exercise 3.5) that the solution to (3.41) can be separated into two parts, after reparametrization using centered inputs: each $x_{ij}$ gets replaced by $x_{ij} − \bar{x}_j$ . We estimate $\beta_0$ by $ \bar{y} = \frac{1}{N}\sum_1^{N}y_i $. The remaining coefficients get estimated by a ridge regression without intercept, using the centered $x_ij$ . Henceforth we assume that this centering has been done, so that the input matrix X has p (rather than p + 1) columns.
