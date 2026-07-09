# LQR-Inverted-Pendulum-on-Cart
Simulation of an inverted pendulum on a cart system with a Linear Quadratic Regulator (LQR) controller using MATLAB and Simulink.

HOW TO USE
----------
1. Run IPonC_setup.mlx to set parameters, state-space model, and analyze stability
2. Run LQR_step.mlx to set Q dan R matrix variations, then plot the step response of each state and variation. Values for Q, R, K, Nbar, and performance metrics (rise time, settling time, %OS, steady-state error, etc.) can also be shown.
3. Run LQR_sim.mlx to plot simulation results from LQR_assignment_4.slx

Notes: the Simulink results still experience errors in keeping the pendulum upright (it instead tends to oscillate downward) as well as controlling the cart position, will make updates to troubleshoot this sometime in the future :'-D
