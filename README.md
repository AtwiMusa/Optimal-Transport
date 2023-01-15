# Seminar: Entropic optimal transport

I have done this seminar throughtout my master's degree in Scientific Computing at TU Berlin, and the main topic was:

The Linear programming problem may have no unique solution and computing
the optimum is costly, where the complexity turns out to be super cubic which
actually means that it is infeasible for large number of samples. To overcome this
issue, regularization methods have been proposed to approximate the original
problem by adding a multiple of the negative entropy of the transport plan
that forces the solution to have spread support and makes the problem strongly
convex and smooth.

The regularized problem has a unique solution that converge to the optimal
solution minimizing the original problem with minimal entropy. The minimization
is achieved numerically by a simple Sinkhorn algorithm allowing us to compute
the EOT with cost that is quadratic in the number of samples.

 
