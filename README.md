This page focuses on our root-finding based algorithm for computing projections onto the $l_{\infty,1}$-ball. 

The matlab code provides a usage example in the main.m file. The core files in the package are proj_newton_pruned and proj_steffensen_pruned 

[ X,tau_opt,iter ] = proj_steffensen_pruned( B, tau, gamma_0 )

[ X,tau_opt,iter ] = proj_newton_pruned( B, tau, gamma_0 )

B is the input matrix, tau is the constraint parameter and gamma_0 is an optional initial point for the root search algorithm.

*References*

G. Chau, B. Wohlberg, and P. Rodriguez. "Efficient Projection onto the ℓ∞,1 Mixed-Norm Ball using a Newton root search method.", SIAM Journal on Imaging Sciences, 2019, 604-623.

G. Chau, B.Wohlberg and P. Rodriguez, “Fast Projection onto the l∞,1 Mixed Norm Ball using Steffensen Root Search,” 2018 International Conference on Acoustics, Speech and Signal Processing, Calgary, Canada, 2018. 
