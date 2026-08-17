The codes of variational approach and SMatPI are implemented with
python version 3.13.13
numpy version 2.4.6
scipy version 1.17.1
numba version 0.65.1

Variational approach: multiD1code.zip

call maintaskmd1.py or mainmd1funsbm.py to simulate.


Set the pseudomode parameters by the filename; each txt file contains a set of pseudomode parameters with given coupling strength and temperature.
 

MMlist denotes a list of the values of multiplicity M.



SMatPI: SMatPIundriven.zip and SMatPIdriven.zip

Call maindynamics.py to simulate.

Ad sets the value of driving strength.
wd sets the value of driving frequency. 
NN is total number of time step.
dt is time step. 
dKmax is the memory length. 
Kt is the Floquet truncation.



