# SIS-Epidemic-Model

The susceptible-infected-susceptible (SIS) stochastic epidemic model attempts to reproduce
the behavior of epidemics running through a population with no vital dynamics without births
and deaths occurring. In this model it is assumed that no individuals are removed from circulation either by immunization or isolation. In the SIS model, susceptible individuals may
become infected by contact with infective individuals, and hence, it is assumed that there is no
incubation period for the disease; that is, infected individuals become infectious immediately.
Let I(t) ∈ S , {0, 1, 2, . . . , N} denote the number of infected individuals at time t > 0 in
a population of N > 1 individuals. This process can be modeled as a continous time Markov
chain under the following assumptions:

- Homogeneous mixing: Every individual comes into contact with another at random intervals which are independent and identically distributed random variables. The distribution
of these intervals is exponential with parameter κ > 0.

- If a contact involves a susceptible individual and an infectious one, the probability of
infection is θ ∈ (0, 1) hence, λ = κθ is the effective contact rate.

- The duration of the infectious state is an exponential random variable with parameter
µ > 0, that is, µ is the recovery rate.
