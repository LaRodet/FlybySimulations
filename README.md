# FlybySimulations
N-body output of the impact of a flyby on a test particle. Data used in Rodet and Lai (2021, to be submitted).

Each file contains the results of 12,000 numerical simulations for a given dimensionless distance at closest approach q/ap. The two stars have similar mass, their relative trajectory has eccentricity 1.1. The simulation starts and ends when they are separated from 100 x ap, where ap=1 is the initial semi-major axis of the test particle. The integrator used is IAS15 from the Rebound package (Rein and Spiegel 2015).

The first line is "q = ... ap".
The second line contains the name of the columns.
Each following line then corresponds to a simulation.

The first column contains the initial longitude of the test particle (deg), the second and third contains the argument of periastron and inclination of the flyby trajectory with respect ot the test particle's orbital plane (deg). The fourth and fifth columns are the final value of the eccentricity and inclination (deg) of the initially circular test particle. Finally, the last column is the new semi-major axis of the test particle (negative values corresponds to hyperbolic orbits). 
