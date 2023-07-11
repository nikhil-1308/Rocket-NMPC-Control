# Rocket-NMPC-Control
This is a simple simulation of Rocket landing control using Nonlinear MPC. The equations of motion are in 3D, using Newtonian Mechanics. The values chosen are nominal.
The code template is taken from the Matlab's example. The following uses sequential quadratic programming to solve nonlinear programming problem (Matlab's inbuilt function 'fmincon'). 
This method helps better optimize with constraints as the system equations are nonlinear in nature. 
The changing parameters in rocket can be fed back to the controller to better optimize for the given constrained optimization problem, becoming adaptive in nature of control.
