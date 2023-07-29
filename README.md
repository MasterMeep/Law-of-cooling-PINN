# Law-of-cooling-PINN
by implementing a PINN we can aproximate the curve and cooling rate of the cooling function for a specific case with as little as the shown 10 training points covering 1/3 of the functions domain. doing so allows us to train a solver for the ODE with extremely small amounts of data, that still manages to generalize over the domain of the function, and not overfit to the input data. While the cooling equation has been long solved, the PINN method of solving differential equations manages to generalize well to complicated differentials.

# Example (10 training points, 30000 epochs)
![image](https://github.com/MasterMeep/Law-of-cooling-PINN/assets/51376656/00f82560-654e-48da-9880-46b44848d0c6)
